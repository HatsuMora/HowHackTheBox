# HowHackTheBox
Personal notes and cheat sheets on how to do hack the box labs.

# Find ports and basic recon

sudo nmap -sS -A ip -p-

# List sub directories on a web server
```gobuster dir -u ip -w wordlist```
> Useful word lists: 
>
> /usr/share/wordlists/dirb/common.txt

# Files with garbage
```strings file``` Print the printable characters
# Change shell
python -c 'import pty; pty.spawn("/bin/bash")'
