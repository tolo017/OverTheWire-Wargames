# Bandit Level 7 → Level 8

## 🎯 Goal
The password for the next level is stored in the file `data.txt` next to the word `millionth`.

## 🔍 Background
We have a large file and need to find a specific line containing our target word. `grep` is perfect for this.

## 🛠️ Step-by-Step Solution

### Method 1: Search and display the solution
```bash
ls -alps
cat data.txt | grep millionth
```
### Method 2: Basic grep search
```bash
grep "millionth" data.txt
```
### Method 3: Case insensitive search (if unsure of capitalization)
```bash
grep -i "millionth" data.txt
```
### Method 4: Show line number with the match
```bash
grep -n "millionth" data.txt
```

## 🔑 Password Found
The line containing "millionth" had the Level 8 password.

## 💡 Key Concepts Learned
- Text pattern matching with grep
- Searching in large files
- Case sensitivity in Linux commands
- Basic regular expressions
