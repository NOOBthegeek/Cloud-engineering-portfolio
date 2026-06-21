# Day 26 - Processes and System Monitoring

## Commands Learned

- ps aux
- top
- ps aux | grep ssh
- uptime
- free -h
- df -h

## What I Learned

Linux runs programs as processes.

The `ps aux` command displays all running processes on the system.

The `top` command provides a live view of system activity, including CPU and memory usage.

The `ps aux | grep ssh` command can be used to find SSH-related processes.

The `uptime` command shows how long the server has been running and displays system load averages.

The `free -h` command displays memory usage in a human-readable format.

The `df -h` command displays disk space usage in a human-readable format.

## Key Concepts

- Every running program is a process.
- Each process has a Process ID (PID).
- Processes consume CPU and memory resources.
- System monitoring helps identify performance problems.
- Cloud engineers regularly monitor processes, memory, and disk usage.

## Commands Practiced

```bash
ps aux
top
ps aux | grep ssh
uptime
free -h
df -h
```

## Summary

Today I learned how to monitor a Linux server by viewing running processes, checking system uptime, monitoring memory usage, and examining disk usage. These skills are essential for troubleshooting and maintaining cloud servers.
