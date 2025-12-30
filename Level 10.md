## Bandit Level 9 → Level 10

### Objective
Find the password for Bandit Level 10. The password is hidden in a human-readable string within `data.txt` and contains an `=` character.

### Commands Executed
- `ls`
- `strings data.txt | grep "="`

### Explanation
- Used `ls` to list files in the directory.
- Used `strings` to extract readable text from `data.txt`.
- Piped the output to `grep "="` to filter lines containing the `=` character.
- The resulting output revealed the password.

### Password

`FGUW5ilLVJrxX9kMYMmN4MgbpfMiqey`


<img width="578" height="405" alt="image" src="https://github.com/user-attachments/assets/981ff47d-db5f-4479-a17a-c0747ad0f49b" />

