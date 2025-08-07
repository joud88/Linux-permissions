# Linux-permissions
script.py has been granted rwxrwxr-x permissions via chmod, allowing the owner and group to read, write, and execute the script, while others can only read and execute it.






# 📜 Linux File Permissions – script.py

## 🔧 chmod Usage

I used the `chmod` command to change the permissions of a script file named `script.py` to: rwxrwxr-x



### 🔍 What This Means:
| Role      | Permissions | Explanation                                 |
|-----------|-------------|---------------------------------------------|
| **User**  | `rwx`        | Can read, write, and execute the file       |
| **Group** | `rwx`        | Can read, write, and execute the file       |
| **Others**| `r-x`        | Can read and execute, but **not** write     |

The command used:
```bash
chmod 775 script.py



🧩 File Permissions Flowchart
To help visualize how Linux file permissions work, I created a flowchart showing the decision-making process behind read, write, and execute permissions for the user, group, and others.

🖼️ Flowchart Overview
The flowchart helps answer:

Who is trying to access the file?

Do they have read, write, or execute permission?

What actions can they perform based on their role?



✅ Summary
By using chmod, I granted full access to the file owner and group, while giving limited access to others. The accompanying flowchart explains Linux file permissions in a clear, visual way.
