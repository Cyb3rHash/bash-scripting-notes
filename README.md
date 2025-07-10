# 📚 Bash Scripting Compendium  
**By CyberHash | Cybersecurity Student & Linux Enthusiast**  

![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![License](https://img.shields.io/badge/License-CC_BY_4.0-EF9421?style=for-the-badge)
![Progress](https://img.shields.io/badge/Progress-66_Chapters-2CA5E0?style=for-the-badge)

A meticulously organized reference guide covering **66 chapters** of essential Bash scripting knowledge, from fundamentals to advanced techniques, with cybersecurity applications.

---

## 🌟 Features

- **Book-style organization** with 66 chapters and 300+ sections
- **Practical examples** for sysadmins and security professionals
- **Cross-referenced** concepts with clear progression
- **Real-world scenarios** including log analysis and network tools
- **Cheat sheets** for quick reference

---

## 📖 Full Chapter Index

### 🔰 Core Fundamentals
1. **Getting Started with Bash**  
   - Hello World variants, Debug mode, Named arguments
2. **Script Shebang**  
   - Env vs Direct shebangs, Best practices
3. **Navigating Directories**  
   - Absolute/relative paths, Script directory navigation

### 📂 File Operations
4. **Listing Files**  
   - Advanced `ls` techniques, Tree views, Sorting
5. **Using `cat`**  
   - Concatenation, Non-printable chars, Gzipped files
6. **File Transfer with `scp`**  
   - Secure copy techniques

### 🔍 Text Processing
7. **`grep` Patterns**  
   - File searching techniques
8. **`cut` Command**  
   - Column extraction, Delimiter handling
9. **`sort` Utilities**  
   - Numeric sorting, Unique outputs

### ⚙️ System Control
10. **Jobs & Processes**  
    - Background jobs, Port monitoring, Process info
11. **Job Control**  
    - Foreground/background management
12. **Signal Handling with `trap`**  
    - Cleanup scripts, Child process management

### 📊 Advanced Scripting
13. **Control Structures**  
    - If/else, Case statements, Loops
14. **Functions**  
    - Parameter handling, Return values
15. **Arrays**  
    - Indexed/associative arrays, Modifications

*...Continues through 66 chapters. Full index available in [INDEX.md](./INDEX.md)*

---

## 🛠️ Quick Start

```bash
# Clone repository
git clone https://github.com/Cyb3rHash/bash-scripting-reference.git
cd bash-scripting-reference

# Search for a topic
grep -rin "named arguments" .

# Run an example script
chmod +x examples/network_scanner.sh
./examples/network_scanner.sh
```

---

## 🎯 Key Chapters for Security Professionals

| Chapter      | Security Application        |
|--------------|----------------------------|
| 6. Grep      | Log analysis patterns       |
| 17. Find     | Forensic file location      |
| 42. SCP      | Secure file transfers       |
| 47. Trap     | Script hardening            |
| 62. Networking | Service enumeration      |

---

## 📌 Usage Tips

1. Bookmark the [Cheat Sheets](./cheatsheets/) folder
2. Use `Ctrl+F` in markdown files for quick searching
3. All examples tested on:
   - Kali Linux 2023+
   - Ubuntu 22.04 LTS
   - WSL2 environments

---

## 🌱 Contributing

While this is primarily a personal reference, suggestions are welcome:

1. Open an Issue for corrections
2. Fork for personal adaptations
3. Star if you find it valuable!

**Credit:** Please attribute to [CyberHash](https://github.com/Cyb3rHash) when referencing.

---

## 📜 License

Creative Commons Attribution 4.0 ([CC BY 4.0](https://creativecommons.org/licenses/by/4.0/))

- ✅ Modify and redistribute
- ✅ Use commercially
- ❌ No warranty provided

[![License Badge](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

---

> "Mastery of the command line is the foundation of cybersecurity prowess."  
> — **CyberHash**