# Nmap Basics

Only scan systems you own or have written permission to test.

```bash
nmap -sV -T4 target.example        # service/version detection
nmap -p- target.example            # all TCP ports
nmap -sC -sV -oN scan.txt target   # default scripts, save output
```
