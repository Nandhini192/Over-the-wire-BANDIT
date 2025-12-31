## Bandit Level 16 → Level 17

### Objective
Obtain an RSA private key via an SSL connection and use it to log in to Bandit Level 17.

### Commands Executed
- `ncat --ssl localhost 31790`
- *(Saved the RSA private key output to a file named `key17`)*
- `chmod 600 key17`
- `ssh -i key17 bandit17@bandit.labs.overthewire.org -p 2220`
- `cat /etc/bandit_pass/bandit17`

### Explanation
- Connected to the SSL service on port `31790` using `ncat`.
- Captured the RSA private key provided by the service.
- Secured the private key with proper file permissions.
- Logged in to Bandit Level 17 using SSH key authentication.
- Read the password file for the next level.

### Password

`EREvavePLFHtFlEsjn3hyzmlvSuSAcRD`






<img width="529" height="482" alt="image" src="https://github.com/user-attachments/assets/ec5ba5a8-a407-48ac-90eb-398233feccb2" />




<img width="558" height="489" alt="image" src="https://github.com/user-attachments/assets/cb9dcaaf-45d5-4e1d-857d-f43a08408176" />



<img width="567" height="460" alt="image" src="https://github.com/user-attachments/assets/b7c3b7ec-ddb3-45fc-a569-5b11f5d9620e" />



<img width="438" height="37" alt="image" src="https://github.com/user-attachments/assets/868e79f1-45bb-4e1c-806c-7f2921e39e53" />




