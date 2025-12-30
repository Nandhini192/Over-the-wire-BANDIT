## Bandit Level 7 → Level 8

### Objective
Find the password for Bandit Level 8. The password is stored in `data.txt` next to the word **millionth**.

### Commands Used
- `ls`
- `grep millionth data.txt`
- `grep millionth data.txt | awk '{print $2}'`

### Explanation
- Used `ls` to list files in the directory.
- Used `grep millionth data.txt` to locate the line containing the word **millionth**.
- Piped the output to `awk '{print $2}'` to extract the password, which is the second field on that line.

### Password

dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc



<img width="724" height="137" alt="image" src="https://github.com/user-attachments/assets/4bb38310-dede-4f28-903d-46fbbf0dddd5" />


