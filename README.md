# Linux-permissions
script.py has been granted rwxrwxr-x permissions via chmod, allowing the owner and group to read, write, and execute the script, while others can only read and execute it.






## 🔐 Linux File Permissions Flowchart

```mermaid
flowchart TD
    A[Start] --> B{Do you own the file?}
    B -- Yes --> C[Use Owner permissions (rwx)]
    B -- No --> D{Are you in the file's group?}
    D -- Yes --> E[Use Group permissions (rwx)]
    D -- No --> F[Use Others permissions (rwx)]
    C --> G[Can Read? -> r]
    C --> H[Can Write? -> w]
    C --> I[Can Execute? -> x]
    E --> G
    E --> H
    E --> I
    F --> G
    F --> H
    F --> I
