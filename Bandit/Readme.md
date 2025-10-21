# Bandit Series - Linux Command Line Mastery 🐧

> *"From zero to hero in Linux command-line and basic security"*

## 🎯 What is Bandit?

The Bandit wargame is your **first step** into cybersecurity through OverTheWire. It's designed for **absolute beginners** who want to master the Linux command line while learning essential security concepts.

### 🎮 Perfect For:
- Linux newbies wanting hands-on practice
- Aspiring cybersecurity professionals
- Anyone who learns by doing, not just reading

### 🛠️ Skills You'll Master:
- Navigating Linux file systems
- File permissions and ownership
- Text processing commands
- Network connections
- Basic scripting and automation
- Critical thinking and problem-solving

---

## 📚 Level-by-Level Journey

### **Level 0 → Level 1**
**First Contact: Connecting to the Game**
- **Goal:** Learn SSH basics and make your first connection
- **Key Concept:** Remote server access
- **Command:** `ssh`

### **Level 1 → Level 2**
**Reading Special Files**
- **Goal:** Read a file named `-` (dash)
- **Key Concept:** Special filename handling
- **Commands:** `cat`, specifying file paths correctly

### **Level 2 → Level 3**
**Spaces in Filenames**
- **Goal:** Read a file with spaces in its name
- **Key Concept:** Escaping special characters
- **Commands:** `cat "filename with spaces"`

### **Level 3 → Level 4**
**Hidden Files**
- **Goal:** Find a hidden file in a directory
- **Key Concept:** Linux hidden files (starting with `.`)
- **Commands:** `ls -a`

### **Level 4 → Level 5**
**File Types Discovery**
- **Goal:** Identify which file is human-readable
- **Key Concept:** Determining file types
- **Commands:** `file`, `find`

### **Level 5 → Level 6**
**Finding Specific Files**
- **Goal:** Locate a file with specific properties
- **Key Concept:** File search criteria
- **Commands:** `find` with size and ownership filters

### **Level 6 → Level 7**
**System-Wide File Search**
- **Goal:** Find a file somewhere on the entire system
- **Key Concept:** Searching from root directory
- **Commands:** `find /`

### **Level 7 → Level 8**
**Text Processing Basics**
- **Goal:** Extract password from a large file
- **Key Concept:** Filtering file content
- **Commands:** `grep`

### **Level 8 → Level 9**
**Finding Unique Lines**
- **Goal:** Locate the only unique line in a file
- **Key Concept:** Data comparison and filtering
- **Commands:** `sort`, `uniq`

### **Level 9 → Level 10**
**Human-Readable Strings**
- **Goal:** Find readable text in binary data
- **Key Concept:** Extracting text from any file
- **Commands:** `strings`

### **Level 10 → Level 11**
**Base64 Decoding**
- **Goal:** Decode base64 encoded data
- **Key Concept:** Data encoding/decoding
- **Commands:** `base64 -d`

### **Level 11 → Level 12**
**ROT13 Encryption**
- **Goal:** Decode ROT13 encoded text
- **Key Concept:** Simple substitution ciphers
- **Commands:** `tr`

### **Level 12 → Level 13**
**File Compression Recognition**
- **Goal:** Deal with multiple compression formats
- **Key Concept:** Archive and compression types
- **Commands:** `gzip`, `bzip2`, `tar`, `xxd`

### **Level 13 → Level 14**
**SSH Keys**
- **Goal:** Use a private SSH key to connect
- **Key Concept:** Key-based authentication
- **Commands:** `ssh -i`

### **Level 14 → Level 15**
**Network Services**
- **Goal:** Submit password to a network service
- **Key Concept:** Client-server communication
- **Commands:** `telnet`, `nc`

### **Level 15 → Level 16**
**SSL/TLS Connections**
- **Goal:** Use SSL to submit data
- **Key Concept:** Secure network connections
- **Commands:** `openssl s_client`

### **Level 16 → Level 17**
**Port Scanning**
- **Goal:** Find open ports on a server
- **Key Concept:** Network reconnaissance
- **Commands:** `nmap`

### **Level 17 → Level 18**
**File Comparison**
- **Goal:** Find differences between two files
- **Key Concept:** Data comparison
- **Commands:** `diff`

### **Level 18 → Level 19**
**SSH with Commands**
- **Goal:** Execute commands via SSH without interactive login
- **Key Concept:** Remote command execution
- **Commands:** `ssh command execution`

### **Level 19 → Level 20**
**Setuid Binaries**
- **Goal:** Exploit a binary with special permissions
- **Key Concept:** Privilege escalation basics
- **Commands:** `./binary_name`

### **Level 20 → Level 21**
**Network Daemons**
- **Goal:** Interact with a running service
- **Key Concept:** Process management and networking
- **Commands:** `nc`, `&` (background processes)

### **Level 21 → Level 22**
**Cron Jobs**
- **Goal:** Understand and exploit scheduled tasks
- **Key Concept:** Automated task scheduling
- **Commands:** `crontab`

### **Level 22 → Level 23**
**Advanced Cron**
- **Goal:** Work with user-specific cron jobs
- **Key Concept:** User-level automation
- **Commands:** `crontab -l`, `crontab -e`

### **Level 23 → Level 24**
**Scripting with Cron**
- **Goal:** Write and schedule your own script
- **Key Concept:** Basic shell scripting
- **Commands:** Shell scripting basics

### **Level 24 → Level 25**
**Brute Force Protection**
- **Goal:** Create a brute-force protection bypass
- **Key Concept:** Timing attacks and automation
- **Commands:** Shell loops, scripting

### **Level 25 → Level 26**
**Advanced Shell Escape**
- **Goal:** Escape from a restricted shell
- **Key Concept:** Shell restrictions and escapes
- **Commands:** Terminal resizing tricks

### **Level 26 → Level 27**
**Setuid with Arguments**
- **Goal:** Exploit a setuid binary with arguments
- **Key Concept:** Advanced binary exploitation
- **Commands:** Command injection

### **Level 27 → Level 28**
**Git Repository Analysis**
- **Goal:** Clone and analyze a git repository
- **Key Concept:** Version control security
- **Commands:** `git`

### **Level 28 → Level 29**
**Git Log Analysis**
- **Goal:** Find sensitive information in git history
- **Key Concept:** Information disclosure in version control
- **Commands:** `git log`, `git show`

### **Level 29 → Level 30**
**Git Branching**
- **Goal:** Check other branches for secrets
- **Key Concept:** Git branching and merging
- **Commands:** `git branch`, `git checkout`

### **Level 30 → Level 31**
**Git Tagging**
- **Goal:** Explore git tags for hidden data
- **Key Concept:** Git tag objects
- **Commands:** `git tag`

### **Level 31 → Level 32**
**Git Push Exploitation**
- **Goal:** Add files to a remote repository
- **Key Concept:** Git remote operations
- **Commands:** `git push`

### **Level 32 → Level 33**
**Uppercase Shell Escape**
- **Goal:** Escape from a shell that uppercases all commands
- **Key Concept:** Advanced shell escaping techniques
- **Commands:** Special shell variables

### **Level 33 → Level 34**
**Final Challenge**
- **Goal:** Complete the Bandit series
- **Key Concept:** Putting all skills together
- **Commands:** Everything you've learned!

---

## 🏆 My Progress

| Levels | Status | Completion Date |
|--------|--------|-----------------|
| 0-5 | ✅ Completed | 21/10/2025 |
| 6-10 | 🔄 In Progress | - |
| 11-20 | ⏳ Planned | - |
| 21-34 | ⏳ Planned | - |

---

## 🚀 Getting Started

Ready to begin your Bandit journey?

```bash
# Start at Level 0
ssh bandit0@bandit.labs.overthewire.org -p 2220
Password: bandit0
```

## 💡 Pro Tip

Read the MAN pages.
MAN command_name is your best friend.
