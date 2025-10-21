# Bandit Level 3 → Level 4

## 🎯 Goal
Find the hidden file in the `inhere` directory and read its contents.

## 🔍 Background
This level teaches us about **hidden files** in Linux. Files that start with a dot (`.`) are normally hidden, but this level introduces another twist - a file that starts with multiple dots!

The file `...Hiding-From-You` is interesting because:
- It starts with multiple dots (`...`)
- It's not a traditional hidden file (which starts with just one dot)
- But it won't show up in normal `ls` listings

## 🛠️ Solutions

### Step 1: Navigate to the correct directory
```bash
cd inhere
```
### Step 2: List ALL files (including hidden and special files)
```bash
ls -a
```
### Step 3: Read the special file
```bash
cat ...Hiding-From-You
```

### Alternatively
```bash
cat inhere/...Hiding-From-You
```

## 🔑 Password Found
The file `...Hiding-From-You` contains the password for Level 4.

## 💡 Key Concepts Learned
- Hidden files in Linux (dotfiles)
- Files with multiple leading dots - not traditional hidden files but still hidden from normal view
- The ls -a command to reveal all files
- Navigating directories with cd
