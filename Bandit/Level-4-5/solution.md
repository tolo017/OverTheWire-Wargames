# Bandit Level 4 → Level 5

## 🎯 Goal
The password for the next level is stored in the only human-readable file in the `inhere` directory.

## 🔍 Background
In the `inhere` directory, there are multiple files named `-file00` to `-file09`. Most are binary/data files, but one is ASCII text (human-readable).

The `file` command examines file signatures to determine actual file type, regardless of the filename.

## 🛠️ Step-by-Step Solution

### Step 1: Navigate to the inhere directory
```bash
cd inhere
```
### Step 2: Check all file types at once
```bash
file ./*
```
### Step 3: Identify the ASCII text file
The output will show one file as "ASCII text"
### Step 4: Read the human-readable file
```bash
cat ./-file07
```

### Alternatively: One-liner solution
file inhere/* | grep ASCII | cut -d: -f1 | xargs cat

## 🔑 Password Found
The ASCII text file contains the Level 5 password.

## 💡 Key Concepts Learned
- File signatures and magic numbers
- `file` command for type detection
- Distinguishing between binary and text files
- Wildcard patterns (`*`)
