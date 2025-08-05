# Linux-permissions
script.py has been granted rwxrwxr-x permissions via chmod, allowing the owner and group to read, write, and execute the script, while others can only read and execute it.





---

### ✅ **Option 2: ASCII Flowchart** (For plain Markdown)

```markdown
## 🔐 Linux File Permissions Flowchart (ASCII)

        +--------+
        | Start  |
        +---+----+
            |
            v
  +----------------------+
  | Do you own the file? |
  +----------------------+
       |         |
      Yes       No
       |         |
       v         v
+------------------+     +-----------------------------+
| Use Owner perms  |     | Are you in the file's group?|
+------------------+     +-----------------------------+
                             |            |
                            Yes          No
                             |            |
                             v            v
                 +------------------+   +-------------------+
                 | Use Group perms  |   | Use Others perms  |
                 +------------------+   +-------------------+

  All permissions checked in: read (r), write (w), execute (x)
