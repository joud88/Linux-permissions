# Linux-permissions
script.py has been granted rwxrwxr-x permissions via chmod, allowing the owner and group to read, write, and execute the script, while others can only read and execute it.


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
