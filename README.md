# 📜 get_next_line — Read a File Line by Line

A function that reads a file descriptor and returns the next line each time it's called. The implementation must handle dynamic memory, partial reads, different file descriptors, and buffer management efficiently.

---

## 🧠 Concepts & Skills Learned
- File descriptors (`open`, `read`, `close`)
- Static variables for persistent state
- Dynamic allocation & memory hygiene
- Handling multiple FDs simultaneously
- Buffer-based reading

---

## 🛠 Prototype
```c
char *get_next_line(int fd);
```
## 📦 Usage
```bash
git clone https://github.com/Jnba23/get_next_line.git
cd get_next_line
```
Include in your project:
#include "get_next_line.h"
### Usage Example :
gcc main.c get_next_line.c get_next_line_utils.c
