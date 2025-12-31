## Bandit Level 25 → Level 26

### Objective
Log in to Bandit Level 26 using an SSH key and escape the restricted shell to retrieve the password.

### Commands Executed
- `ls`
- `file bandit26.sshkey`
- `exit`
- `scp -P 2220 bandit25@bandit.labs.overthewire.org:/home/bandit25/bandit26.sshkey .`
- `ssh -i bandit26.sshkey bandit26@bandit.labs.overthewire.org -p 2220`
- `:set shell=/bin/bash`
- `:shell`
- `cat /etc/bandit_pass/bandit26`

### Explanation
- Identified the SSH private key file.
- Copied the SSH key from the remote server using `scp`.
- Logged in as `bandit26` using key-based authentication.
- Escaped the restricted `more` shell by setting the shell to `/bin/bash`.
- Accessed a normal shell and read the password file.

### Password

`s0773xxkk0MXfdQfPRVr9L3jJBU0gCZ`



<img width="529" height="238" alt="image" src="https://github.com/user-attachments/assets/7f2f4910-a0d2-41bc-b437-1376aa973112" />

