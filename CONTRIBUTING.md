# 🤝 Contributing Guidelines
> We welcome contributions from all Cyber Saguaro members!

To keep our repo organized, please follow these steps and rules:

### 🗂️ File & Folder Placement Rules
- Python/ → All Python scripts, exploits, crypto tools, automation, and projects.
> -  Algorithms/ → Sorting, searching, and data structure implementations.
> -  CTF-Scripts/ → Python used for pwning, reversing, crypto, web automation in CTFs.
> -  Web-Scraping/ → Requests, BeautifulSoup, Selenium, etc.
> -  Projects/ → Full Python programs, tools, or apps.
- Web/ → Anything related to frontend/back-end web development or web exploitation.
> - JavaScript/ → Normal JS projects and CTF exploitation scripts (XSS payloads, Node.js challenges).
> - HTML-CSS/, HTML5-Canvas/, Frontend-Projects/ → Web learning and dev projects.
> - Fullstack/ → Multi-tiered apps (Django + React, MERN stack, etc.).
- C/ and Cpp/ → Low-level programming, binary exploitation, system-level projects.
> - Use C/ for raw systems/pwn code and Cpp/ for competitive programming or higher-level applications.
- Assembly/ →
> - Basics/ → Hello World, syscall demos, register exercises.
> - Reverse-Engineering/ → Crackmes, reversing practice.
> - Projects/ → Assembler-coded utilities and experiments.
- Other-Languages/ → Languages not core but still relevant in CTFs or tooling:
> - Shell/ → Bash/Zsh automation scripts, recon helpers.
> - PowerShell/ → Windows exploitation, AD enumeration, post-exploitation.
> - PHP/ → Legacy CTF web exploits (LFI, RFI, SQLi, file upload).
> - Ruby/ → Metasploit-related scripts, older exploits.
> - Perl/ → Legacy tools/scripts.
> - Java/ → Android reversing, JVM challenges, backend utilities.
> - Rust/ and Go/ → Systems tools, network utilities, CTF helper binaries.
- Docs/
> - Each language has its own docs/ folder for cheat sheets, tutorials, install guides, and notes.
> - If you’re adding reference material (not code), put it under the language’s docs/ folder.
---

### 📝 Naming Conventions

- Use descriptive filenames `rsa_decrypt.py` instead of `script1.py`
- Use `snake_case` for Python, Shell, and PowerShell scripts.
- Use `camelCase` or `PascalCase` for Java, C, and C++ files depending on project conventions.
- Avoid spaces in file/folder names `—` use `_` or `-`.
---

### 💾 Commits & Branches

- Create feature branches:
  `git checkout -b add-rsa-decrypt-script`
- Use clear commit messages:
  > "Added Python script for RSA decryption (crypto CTF)"
  > "Fixed buffer overflow exploit in C (pwn challenge)"
  > "Updated Web/JavaScript docs with XSS payload notes"
---

### ✅ Pull Request Checklist

Before opening a PR:
> Code is placed in the correct language/category folder <br>
> Docs (if any) are added to the right docs/ subfolder <br>
> File follows naming conventions <br>
> Code is tested and runs as expected <br>
> Commit message clearly explains what was added <br>

⚡ Following these rules will keep our repo clean and make it a powerful resource for both learning and CTF competitions.
