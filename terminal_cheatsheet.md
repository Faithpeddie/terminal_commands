# Terminal Commands Cheatsheet 💻

**Terminal**
: a **command-line interface** which enables interactions on a MacBook using **text commands.**

Terminal originates from **UNIX**, therefore the core commands can be used on other systems.

Terminal is a **shell** which runs **UNIX text commands.**

### Navigating the File System
| Command | Function |
|----------|----------|
| `pwd` | shows current folder location |
| `ls` | lists files & folders in current directory |
| `ls -l` | lists files & folders with permissions, owners and date last modified|
| `ls -al` | lists files & folders including hidden files |
| `cd` | allows movement into a directory |
| `cd -` | allows movement into the previous directory |
| `cd bnta_work/week_01` | allows momement through multiple folders |
| `tab` key | auto-completes different commands |

### Creating Files and Folders
| Command | Function |
|----------|----------|
| `mkdir` | creates a new directory [^1] |
| `touch` | creates a new file [^2] |

### Opening Files 
| Command | Function |
|----------|----------|
| `open` | opens in text editor |
| `code` | opens in VSCode |

### Manipulating Files and Folders
| Command | Function |
|----------|----------|
| `mv` | moves a file |
| `..` | shortcut to the directory a level above **OR** used to rename a file [^3] |
| `cp` | copies a file into another location [^4] |
| `rm` | deletes a file [^5] |
| `- r` flag| recursive (an entire directory & content) |
| `- f` flag| force (bypasses confirmation) | 

[^1]: Use **CamelCase** or an **under_score**.

[^2]: File must be named with the **file extension** `.txt`, `png`, `pdf` *etc.*

[^3]: *E.g.* `mv cheatsheed.md cheatsheet.md`

[^4]: *E.g.* `cp cheatsheet.md terminal_commands`

[^5]: *E.g.* `rm cheatsheet.md`

## 🍋 Easy peasy lemon squeezy 🍋