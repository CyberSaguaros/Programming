# 📚 Shell (Bash/Zsh) Resources

This folder contains **resources, guides, and notes** for Shell scripting, automation, and quick tooling.

---

## 📖 Getting Started
- Run a script:  
  ```
  chmod +x script.sh
  ./script.sh
  ```
---

## 🛠️ Common Use Cases in CTFs
- Automation → Looping brute force attempts, chaining tools.
- Forensics → Quickly parsing files (grep, awk, cut, strings).
- Networking → Using nc, curl, and wget for challenges.
- Binary Exploits → Launching processes with input redirection.
---

## 🔑 Cheat Sheets
- Loop:
```
for i in {1..100}; do
  echo "Try $i"
done
```
- Grep in files:
```
grep -r "flag" .
```
- Netcat listener:
```
nc -lvnp 4444
```
---

## 🌍 External References
- [Explainshell](https://explainshell.com/) – great for understanding one-liners.
- [GTFOBins](https://gtfobins.github.io/) – privilege escalation tricks.
- [Bash Hackers Wiki](https://github.com/rawiriblundell/wiki.bash-hackers.org/blob/main/start.md) – deep dive into Bash.
---
