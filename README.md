# Carlos Silva — CodexSC

> *"Πᾷ βῶ, καὶ χαριστίωνι τὰν γᾶν κινήσω πᾶσαν."*  
> **"Give me a place to stand and a lever, and I will move the whole earth."** — Archimedes

DEV trained at **Holberton School**, focused on building computer solutions from the engine to the fairings.

---

## Featured Projects

### 🐚 [Simple Shell](https://github.com/CodexSC/holbertonschool-simple_shell)
> A fully functional UNIX shell written in C from scratch.

Built alongside D. Rossi as a deep-dive into how shells actually work. Implements the complete command execution pipeline — `getline` → tokenization → PATH resolution → `fork` / `execve` / `wait` — with proper error handling, memory management, and both interactive and non-interactive modes.

**Stack:** C · POSIX syscalls · Betty style  
**Highlights:** 104 commits · man page included · execution flowchart documented · live demo on [Vercel](https://holbertonschool-simple-shell.vercel.app)

```c
// The loop that runs the world
while (1) {
    line = read_input();
    tokens = split_line(line);
    if (!handle_builtin(tokens))
        execute_cmd(tokens);
}
```

---

### 🗓️ [Celtic Calendar](https://github.com/CodexSC/CelticCalendar)
> A terminal-based simulation of the ancient Celtic Coligny calendar system.

A personal project combining archaeology, astronomy, and C systems programming. Reconstructs the 2,000-year-old Coligny bronze tablet in a fully navigable ncurses TUI, with real astronomical calculations (Julian day, lunar phases, solar position, zodiac), Celtic festival detection (Samhain, Imbolc, Beltane, Lughnasadh), and authentic Coligny day notation.

**Stack:** C · ncurses · libm · astronomical algorithms  
**Highlights:** 8+ translation units · Unicode/ASCII knotwork rendering · fully keyboard-navigable · MIT licensed

---

### ⚙️ [Low-Level Programming in C](https://github.com/CodexSC/holbertonschool-low_level_programming)
> A comprehensive series on C fundamentals — 320 commits across 15+ modules.

The backbone of my C education, covering every major building block of the language at the systems level. Not exercises in isolation — a cumulative body of work that progresses from basic control flow to complex memory management and I/O.

**Modules covered:**

| Module | Topics |
|---|---|
| Pointers, Arrays & Strings | pointer arithmetic, string manipulation |
| Recursion | base cases, stack depth, recursive algorithms |
| malloc / free | dynamic allocation, heap management, no leaks |
| More malloc / free | `realloc`, complex allocation patterns |
| Function Pointers | callbacks, dispatch tables |
| Variadic Functions | `va_list`, `va_start`, `va_arg` |
| Singly Linked Lists | insertion, deletion, traversal |
| Doubly Linked Lists | bidirectional traversal, node management |
| Structures & typedef | compound types, custom type aliases |
| File I/O | `open`, `read`, `write`, `close`, file descriptors |
| argc / argv | command-line argument parsing |

---

### 🐚 [Shell Scripting](https://github.com/CodexSC/holbertonschool-shell)
> Bash scripting fundamentals — navigation, permissions, variables, I/O, and process management.

**Stack:** Bash · Unix utilities

---

### 🤖 [AI-Assisted Debugging](https://github.com/CodexSC/holbertonschool-chatgpt-introduction)
> Practical use of LLMs for improving code quality, finding bugs, and explaining logic.

**Stack:** Python · HTML  
**Focus:** Prompt engineering for debugging, AI-driven code review workflows

---

## Skills

| Domain | Technologies |
|---|---|
| Systems Programming | C, POSIX APIs, process control, file descriptors |
| Memory | `malloc` / `free` / `realloc`, zero-leak discipline, `valgrind` |
| Data Structures | singly & doubly linked lists, function pointers, structs |
| Shell | Bash, shell scripting, Unix toolchain |
| Tooling | gcc, gdb, valgrind, make, git |
| Practices | Betty style guide, man pages, modular headers, include guards |

---

## Languages

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

---

## Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=CodexSC&show_icons=true&theme=dark&hide_border=true&count_private=true" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=CodexSC&layout=compact&theme=dark&hide_border=true" height="165" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=CodexSC&theme=dark&hide_border=true" />
</p>

---

## Education

**Holberton School** — Full-Stack Software Engineering  
Curriculum grounded in Low and High Level Languages with Augmented Capabilities.

---

## Contact

[![GitHub](https://img.shields.io/badge/GitHub-CodexSC-181717?style=flat&logo=github)](https://github.com/CodexSC)

---

<sub>*"The Unix philosophy: Do one thing and do it well."* — Ken Thompson</sub>
