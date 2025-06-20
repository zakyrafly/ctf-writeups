# Writeup: HTB Lab - Cap
![alt text](/images/Cap.png)
## Task 1: How many TCP ports are open?
To find out how many TCP ports are open, we can use the `nmap` command with the target IP Address

```
nmap -sC -sV 192.168.1.100
```
![alt text](/images/task1.png)
**The answer is: 3**

## Task 2: After running a "Security Snapshot", the browser is redirected to a path of the format /[something]/[id], where [id] represents the id number of the scan. What is the [something]?
At first I was confused on what the question meant by "Security Snapshot", I tried a few more nmap commands but got nothing. So I just tried to enter the IP address of the target into my browser and voila I found it.
![security dashboard](/images/task2.png)
After that I just went into the "Security Snapshots" menu and the answer is in the url
![security snapshot](/images/task2b.png)
**The answer is: data**
