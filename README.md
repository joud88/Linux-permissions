# Linux-permissions
script.py has been granted rwxrwxr-x permissions via chmod, allowing the owner and group to read, write, and execute the script, while others can only read and execute it.


<pre> ``` 📂 Linux File Permissions Flowchart +-----------------------+ | Linux File Access | +-----------------------+ | v +-------------------------------+ | Who wants to access file? | +-------------------------------+ / | \ v v v [User] [Group] [Others] | | | +-------+------+ +----+----+ +------+------+ | Check user r | | Check g | | Check o | | w x perms | | perms | | perms | +-------+------+ +----+----+ +------+------+ | | | +---------+----+ +----+----+ +----+---------+ | Read? (r) | | Write? | | Execute? | +----+----------+ +----+----+ +------+-------+ | | | +------+-----+ +------+----+ +-----+------+ | Can read | | Can write | | Can execute| +------------+ +-----------+ +------------+ ``` </pre>
