# Bandit Level 6 → Level 7

## 🎯 Goal
The password is stored somewhere on the server and has these properties:
- Owned by user `bandit7`
- Owned by group `bandit6`
- 33 bytes in size

## 🔍 Background
First system-wide search! We search from root (`/`) but will see many "Permission denied" errors since we can't read all directories.

## 🛠️ Step-by-Step Solution

### Step 1: Search the entire system
```bash
find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
```
### Step 2: Read the found file
```bash
cat /var/lib/dpkg/info/bandit7.password
```

## 🔑 Password Found
System search located the password file for Level 7.

## 💡 Key Concepts Learned
- System-wide file searching
- Error stream redirection (`2>/dev/null`)
- Finding files by ownership (`-user, -group`)
- Understanding permission limitations
