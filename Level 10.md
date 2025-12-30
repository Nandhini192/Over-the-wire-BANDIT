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



<img width="599" height="408" alt="image" src="https://github.com/user-attachments/assets/0aa9e5fb-6f14-486e-be2c-f0ea0847b24f" />
