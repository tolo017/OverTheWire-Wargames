# Bandit Level 1 → Level 2

## 🎯 Goal
Read the password from a file named `-` (just a dash character).

## 🔍 Background
In Linux, the `-` character has special meaning. It often represents:
- Standard input (stdin) when reading
- Standard output (stdout) when writing

This means when you try `cat -`, it waits for keyboard input instead of reading a file.

## 🛠️ Solutions

### Method 1: Specify the full path
```bash
cat ./-
```
This tells Linux "this is a file in the current directory," not a special character.


### Method 2: Use input redirection
```bash
cat < -
```
The < symbol says "read from this file" instead of treating - as stdin.


### Method 3: Use absolute path
```bash
cat /home/bandit1/-
```
Absolute paths do not get confused with special characters.

## 🔑 Password Found
The password found will be used for Level 2.

## 💡 Key Concepts Learned
- Special filenames in Linux
- Current directory reference (./)
- Input redirection (<)
- Absolute vs relative paths
