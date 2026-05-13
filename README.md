# Carlos Silva — CodexSC
 
> *"Πᾷ βῶ, καὶ χαριστίωνι τὰν γᾶν κινήσω πᾶσαν."*
> **"Give me a place to stand, and I will move the whole earth."** — Archimedes
 
DEV trained at **Holberton School**, focused on systems programming and low-level to high development. 
 
---
 
## Featured Projects
 
### 🐚 [Simple Shell](https://github.com/CodexSC/holbertonschool-simple_shell)
> A fully functional UNIX shell written in C from scratch.
 
Built alongside D. Rossi as a deep-dive into how shells actually work. Implements the complete command execution pipeline — `getline` → tokenization → PATH resolution → `fork` / `execve` / `wait` — with proper error handling, memory management, and both interactive and non-interactive modes.
 
**Stack:** C · POSIX syscalls · Betty style  
**Highlights:** 104 commits · man page included · flowchart documented · live demo on [Vercel](https://holbertonschool-simple-shell.vercel.app)
 
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
**Highlights:** Modular architecture across 8+ translation units · Unicode/ASCII knotwork rendering · keyboard-navigable interface
 
---
 
## Skills
 
| Domain | Technologies |
|---|---|
| Systems | C, POSIX APIs, memory management, process control |
| Shell | Bash, shell scripting, Unix toolchain |
| Languages | C · Python · Java · Shell |
| Tooling | gcc, gdb, valgrind, make, git |
| Practices | Betty style, man pages, modular headers, zero memory leaks |
 
---
 
## Stats
 
![CodexSC's GitHub Stats](https://github-readme-stats.vercel.app/api?username=CodexSC&show_icons=true&theme=dark&hide_border=true&count_private=true)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=CodexSC&layout=compact&theme=dark&hide_border=true)
 
---
 
## Education
 
**Holberton School**
Curriculum grounded in C, low-level programming, algorithms, and systems design before moving up the stack.
 
---
 
## Contact
 
[![GitHub](https://img.shields.io/badge/GitHub-CodexSC-181717?style=flat&logo=github)](https://github.com/CodexSC)
 
---
 
<sub>*"The Unix philosophy: Do one thing and do it well."* — Ken Thompson</sub>
 
