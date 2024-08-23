# SSHBruteForce-Py
This Python script attempts to brute-force SSH passwords using a wordlist. It utilizes the `pwntools` library for the SSH connection and `paramiko` for handling SSH authentication

Key Features:
1. Reads passwords from a wordlist (e.g., `rockyou.txt`).
2. Attempts to connect to an SSH server using each password.
3. Prints valid passwords if found.

Usage:
Ensure that the SSH service is running on the target machine.

Run the script using-

python3 ssh_brute_force.py
