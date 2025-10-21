# Bandit Level 2 → Level 3

## 🎯 Goal
Read the password from a file with spaces and dashes in its name: `--spaces in this filename--`

## 🔍 Background
This filename has **TWO tricky parts**:
1. **Spaces** - normally separate command arguments
2. **Leading dashes** (`--`) - often indicate command options/flags

When you try:
```bash
cat --spaces in this filename--
```
The shell thinks `--spaces` is a command option and tries to read files: `in, this, filename--`

## 🛠️ Solutions

### Method 1: Use ./ to indicate it is a file
```bash
cat ./"--spaces in this filename--"
```
It says "this is a file in the current directory".

### Method 2: Use the --option separator
```bash
cat -- "--spaces in this filename--"
```
-- This says, "everything after this is a filename, not an option."

### Method 3: Use absolute path
```bash
cat /home/bandit2/"--spaces in this filename--"
```

### Method 4: Escape spaces and handle dashes
```bash
cat -- --spaces\ in\ this\ filename--
```

## 🔑 Password Found
Password retrieved for Level 3 access.

## 💡 Key Concepts Learned
- Command-line argument parsing
- Handling filenames that look like options
- The -- option separator trick
- Quoting mechanisms and character escaping
