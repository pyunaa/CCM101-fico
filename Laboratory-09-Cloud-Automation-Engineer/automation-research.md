# Automation Research

## 1. Bash Script

A Bash script is a text file containing Linux commands that can be executed in sequence to automate tasks. The line `#!/bin/bash`, called the shebang, tells the operating system to use the Bash interpreter to run the script.

## 2. Variables

Variables store information, such as directory paths, filenames, or dates, so that the same value can be reused throughout a script. For example, using `$BACKUP_DIR` allows us to change the backup location in one place instead of modifying every command that uses that directory.

## 3. Cron Job

A cron job is a scheduled task in Linux that runs a command or script automatically at a specified time or interval. It is useful in cloud operations because it can automate repetitive tasks such as backups, maintenance, and log cleanup without requiring someone to execute them manually.
