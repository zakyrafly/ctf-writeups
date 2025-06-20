# Writeup: HTB Lab - Cap
![alt text](/images/Cap.png)
## Task 1: How many TCP ports are open?
To find out how many TCP ports are open, we can use the `nmap` command with the target IP Address

```bash
nmap -sC -sV 192.168.1.100