# System Monitoring Script

This bash script provides a snapshot of various system parameters, offering insights into the current state of your Linux system. It covers details such as CPU information, memory usage, disk space, network connections, and more.

## Usage
1. Make sure you have the necessary permissions to execute the script:

    bash
    Copy code
    chmod +x system_monitor.sh

2. Run the script:
 
    bash
    Copy code
    ./system_monitor.sh

## Output

Upon execution, the script will display information on the following aspects:

- **Architecture:** Details about the system architecture.
- **CPU physical:** The number of physical CPUs.
- **vCPU:** The number of virtual CPUs.
- **Memory Usage:** Current RAM usage in MB and percentage.
- **Disk Usage:** Disk space usage in GB and percentage.
- **CPU load:** Current CPU load percentage.
- **Last boot:** Timestamp of the last system boot.
- **LVM use:** Indicates if Logical Volume Management (LVM) is in use.
- **Connexions TCP:** Number of established TCP connections.
- **User log:** Number of users currently logged in.
- **Network:** IP address and MAC address.
- **Sudo:** Number of sudo commands executed.
Notes
The script extracts information directly from various system files and commands.
The results are displayed on the terminal or can be redirected to a log file.
Feel free to use, modify, or share this script as needed.
