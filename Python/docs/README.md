# 📚 Python Resources

This folder contains **resources, guides, and notes** for using Python in Cyber Saguaro projects and CTF competitions.

---

## 📖 Getting Started
- Install: [Python.org Downloads](https://www.python.org/downloads/)  
- Package Manager: `pip install <package>`  
- Recommended Environment: `venv` or [Anaconda](https://www.anaconda.com/)  

---

## 🛠️ Common Use Cases in CTFs
- **Crypto Challenges** → Implementing or breaking ciphers (AES, RSA, XOR).  
- **Web Exploits** → Automating requests with `requests` or `httpx`.  
- **Pwn/Exploits** → Using `pwntools` for binary exploitation.  
- **Automation** → Brute-forcing, regex parsing, scripting.  

---

## 🔑 Cheat Sheets
- Print: `print("Hello World")`  
- Read file:  
  ```python
  with open("file.txt") as f:
      data = f.read()
- Requests:
  ```python
  import requests
  r = requests.get("http://example.com")
  print(r.text)

---

## 🌍 External References
- [Pwntools](https://docs.pwntools.com/en/stable/)
- [CTF Crypto Examples](https://ctf101.org/cryptography/overview/)
- [Python Pentest Tools](https://github.com/dloss/python-pentest-tools)
