# Bandit Level 9 → Level 10

## 🎯 Goal
The password for the next level is stored in the file `data.txt` in one of the few human-readable strings, preceded by several '=' characters.

## 🔍 Background
The file contains binary data with some readable text strings embedded. We need to:
1. Extract human-readable strings
2. Find ones with multiple '=' characters

## 🛠️ Step-by-Step Solution

### Step 1: Extract all readable strings
```bash
strings data.txt
```
### Step 2: Filter for lines with '=' characters
```bash
strings data.txt | grep "="
```
### Step 3: Look for the line with multiple '=' characters
===========thepassword

### Alternatively: One-liner solutions
```bash
cat data.txt | strings | grep ^=
```
OR
```bash
strings data.txt | grep -E "=+"
```

## 🔑 Password Found
Among the extracted strings, one with multiple '=' characters contains the Level 10 password.

## 💡 Key Concepts Learned
- Binary vs text files
- `strings` command for data extraction
- Regular expressions with `grep -E`
- Working with mixed-format files
