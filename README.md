# 🐧 DevOps Learning – Linux Module

This section documents my progress through the Linux fundamentals module.  
I focused on understanding core commands, practicing directly in the terminal, and applying them in small tasks.  

Alongside the lessons, I completed the OverTheWire Bandit wargame (levels 0–12) to strengthen my command line skills in real scenarios.

## Key Topics Covered

- **File & directory navigation**: `ls`, `cd`, `pwd`
- **File operations**: `cp`, `mv`, `rm`, `touch`, `mkdir`
- **Viewing files**: `cat`, `less`, `head`, `tail`
- **Searching & filtering**: `grep`, `find`, `sort`, `uniq`, `cut`
- **Permissions & ownership**: `chmod`, `chown`, `sudo`, `useradd`
- **Compression & encoding**: `gzip`, `gunzip`, `base64`, `tr`, `xxd`
- **Processes & system info**: `ps aux`, `lsof`, `kill`, `df`
- **Text editing**: basic `vim` usage (insert, save, quit)
- **Shortcuts & customisation**: environment variables, aliases, `export`

## Practical Exercises

### OverTheWire Bandit – Levels 0 to 12

To strengthen my Linux skills, I completed the OverTheWire Bandit wargame up to level 12.  
This challenge focuses on applying commands in real scenarios such as file navigation, hidden files, permissions, and data extraction.  

**Key skills and commands used per level:**

- **Level 0 → 1:** Logged in via SSH (`ssh bandit0@bandit.labs.overthewire.org -p 2220`), read a file with `cat`.
- **Level 1 → 2:** Accessed files with spaces in names using quotes or escaping (`cat 'filename with spaces'`).
- **Level 2 → 3:** Listed hidden files (`ls -a`) and viewed contents.
- **Level 3 → 4:** Navigated into unusual directories (`cd inhere`) and opened a file with a specific name.
- **Level 4 → 5:** Identified a human-readable file using `file` command in a directory of binaries.
- **Level 5 → 6:** Used `find` with size and permission filters to locate the password file.
- **Level 6 → 7:** Found a file owned by a specific user/group using `find` with `-user` and `-group`.
- **Level 7 → 8:** Searched within files using `grep` for a specific string.
- **Level 8 → 9:** Located a unique line in a file using `sort` and `uniq -u`.
- **Level 9 → 10:** Searched for human-readable strings inside a binary using `strings`.
- **Level 10 → 11:** Decoded base64 content with `base64 -d`.
- **Level 11 → 12:** Rotated text (ROT13 cipher) using `tr` command.
- **Level 12 → 13:** Extracted a compressed archive step-by-step with `xxd`, `gunzip`, `tar`, and `file`.

Each level reinforced problem solving with command line tools, chaining multiple commands with pipes, and working with file permissions.

## Reflections

- I realised you can only truly understand Linux commands when you **practice directly in the terminal**. Reading alone isn’t enough.  
- When I reached the ROT13 challenge, I was initially confused, but once I understood it, I was amazed at how such a simple cipher could hide information.  
- The biggest improvement came from **trial, error, and persistence**. Even small mistakes taught me more than getting an answer right on the first try.
