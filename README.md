# shell-script1

Clean Cache Script
This script automates the process of cleaning the apt cache and removing unnecessary packages on a Linux system. It performs the following tasks:

Clean the Apt Cache: Uses sudo apt clean to clear out the local repository of retrieved package files.

Remove Unnecessary Packages: Uses sudo apt autoremove to remove packages that were automatically installed to satisfy dependencies for other packages and are no longer needed.

The script logs the success or failure of each operation to a log file located at /home/dev007/cron.log, with each log entry including a timestamp for easy tracking. This ensures you can monitor the maintenance tasks and troubleshoot any issues that may arise.
