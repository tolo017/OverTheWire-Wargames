# Bandit Level 5 → Level 6

## 🎯 Goal
The password is stored in a file somewhere under the `inhere` directory with these properties:
- Human-readable
- 1033 bytes in size
- Not executable

## 🔍 Background
This level introduces advanced file searching with the `find` command. We need to search recursively through all subdirectories of `inhere`.

## 🛠️ Step-by-Step Solution

### Method 1: Search with specific criteria
```bash
find inhere -type f -size 1033c ! -executable
```
### Method 2: Verify if it is readable and show file type
```bash
find inhere -type f -size 1033c -readable ! -executable -exec file {} \;
```
### Method 3: Print the solution
```bash
find inhere -type f -size 1033c -readable ! -executable -exec file {} \; -print
```
### Find the Password
```bash
cat inhere/maybehere07/.file2
```

## 🔑 Password Found
The file matching all criteria contains the Level 6 password.

## 💡 Key Concepts Learned
- Recursive file searching with `find`
- File size specifications (`-size 1033c`)
- Permission-based filtering (`! -executable`)
- Searching in subdirectories

