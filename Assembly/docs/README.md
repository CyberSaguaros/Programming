# 📚 Assembly Resources

This folder contains **resources, guides, and notes** for Assembly, reverse engineering, and binary exploitation.

---

## 📖 Getting Started
- Install [NASM](https://www.nasm.us/): `sudo apt install nasm`  
- Compile:  
  ```
  nasm -f elf64 hello.asm -o hello.o
  ld hello.o -o hello
  ./hello
---

## 🛠️ Common Use Cases in CTFs
- Reverse Engineering → Reading disassembly in Ghidra, IDA, or Radare2.
- Pwn Challenges → Understanding stack frames, syscalls, and registers.
- Malware Analysis → Recognizing common shellcode patterns.
---

## 🔑 Cheat Sheets
- Registers: RAX, RBX, RCX, RDX (general purpose)
- Syscalls: Linux x86-64 syscall table: Syscall Table
- Function Prologue:
```
  push rbp
  mov rbp, rsp
  sub rsp, <size>
```
---
## 🌍 External References
- [CTF 101: Reverse Engineering](https://ctf101.org/reverse-engineering/overview/)
- [Shell-Storm Assembly Database](http://shell-storm.org/shellcode/)
- [x86 Opcode Reference](http://ref.x86asm.net/)
---

