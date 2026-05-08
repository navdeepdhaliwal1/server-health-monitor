# Server Health Monitor

A bash-based system monitoring tool that generates daily health reports
and commits them automatically to GitHub.

## What it monitors
- CPU load average
- Memory usage with alert threshold (>85%)
- Disk usage with alert threshold (>80%)
- Top 5 CPU-consuming processes

## How to run
chmod +x monitor.sh
./monitor.sh

## Automate with cron
0 8 * * * /bin/bash /path/to/monitor.sh

## Sample output
See the `/reports` folder for generated reports.y

