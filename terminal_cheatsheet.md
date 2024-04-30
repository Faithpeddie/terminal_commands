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


## Using Git
| Command | Function |
|----------|----------|
| `git status` | shows the state of the repository including modifications before commiting |
| `git commit -m " "` | creates a detailed record of the modificaions |
|`git revert dr0934` | undo a specific commit using its ID |
| `git log` | displays the commit history of a repository (the most recent at the top) |
| `git reset` | undo a specific commit and every commmit thereafter |
| `git rebase` | reverses and completely removes a series of commits |
| `git remote` | manages (add, remove or modify) remote repositories |
| `git push` | uploads local repository content to a remote repository |
| `git clone` | copies a remote repository |
| `git pull` | uploads changes from a remote repository to a local repository | 

A **repository**:
is a **location** where files are **stored and managed** through the use of **version control**, such as **Git**. 

## 🍋 Easy peasy lemon squeezy 🍋