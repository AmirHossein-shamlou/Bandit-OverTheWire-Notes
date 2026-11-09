# Bandit-OverTheWire-Notes
These are my personal learning notes for the OverTheWire Bandit wargame.

I will document the concepts and commands I learn as I progress.
Passwords, flags, and other sensitive information will not be included.

# Bandit Wargame - OverTheWire

## Level 0 -> Level 1

### Objective
Log in to the remote server via SSH using the provided credentials, and find the password for the next level stored in a file named `readme`.

### Commands Used
```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
ls
cat readme
