# Linux-permissions
script.py has been granted rwxrwxr-x permissions via chmod, allowing the owner and group to read, write, and execute the script, while others can only read and execute it.



## 🔐 Linux File Permission Types

```mermaid
flowchart TD
    A[File Permissions] --> B[Read (r)]
    A --> C[Write (w)]
    A --> D[Execute (x)]
    
    B --> B1[View file contents]
    C --> C1[Modify or delete file]
    D --> D1[Run file as a program/script]



---

If you prefer an **ASCII-style** version for compatibility with all Markdown viewers:

```markdown
## 🔐 Linux File Permission Types (ASCII)

          +------------------+
          | File Permissions |
          +--------+---------+
                   |
    +--------------+--------------+
    |              |              |
    v              v              v
+--------+    +---------+    +------------+
|  Read  |    |  Write  |    |  Execute   |
|   (r)  |    |   (w)   |    |    (x)     |
+---+----+    +----+----+    +-----+------+
    |              |               |
    v              v               v
View file     Modify/delete     Run file as
contents      file content      a program
