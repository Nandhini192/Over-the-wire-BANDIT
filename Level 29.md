## Bandit Level 28 → Level 29

### Objective
Find the password for Bandit Level 29 by inspecting the commit history of a Git repository.

### Commands Executed
- `cd /tmp`
- `mkdir bob`
- `cd /tmp/bob`
- `git clone ssh://bandit28-git@bandit.labs.overthewire.org:2220/home/bandit28-git/repo`
- `cd repo`
- `ls`
- `cat README.md`
- `git log -p`

### Explanation
- Created a working directory in `/tmp`.
- Cloned the Git repository for Bandit Level 28.
- Reviewed the current README (which did not contain the password).
- Used `git log -p` to inspect previous commits and their changes.
- Found the password in an earlier commit.

### Password
 
`4pT1t5DENaYuqnqvadYs1oE4QLCdjmJ7`



<img width="977" height="776" alt="image" src="https://github.com/user-attachments/assets/10837cec-f768-4695-a2ba-1c204af2380e" />




<img width="770" height="783" alt="image" src="https://github.com/user-attachments/assets/b637b036-94a6-4563-a6c8-7e781620d868" />





















