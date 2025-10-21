# Bandit Level 8 → Level 9

## 🎯 Goal
The password for the next level is stored in the file `data.txt` and is the only line of text that occurs only once.

## 🔍 Background
We need to find the unique line in a file with many duplicates. This requires:
1. **Sorting** lines to group duplicates together
2. **Finding unique** lines with `uniq`

## 🛠️ Step-by-Step Solution

### Method 1: Find the only unique line
```bash
sort data.txt | uniq -u
```
### Method 2: Count occurences of each line
```bash
sort data.txt | uniq -c
```
Look for the line with count `1`.
### Method 3: Show only duplicates (For verification)
```bash
sort data.txt | uniq -d
```

## 🔑 Password Found
The unique line contains the Level 9 password.

## 💡 Key Concepts Learned
- Command piping (`|`)
- Text sorting with `sort`
- Duplicate detection with `uniq`
- Data processing workflows
