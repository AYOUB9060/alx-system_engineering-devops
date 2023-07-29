#0x05-processes_and_signals
This directory contains various scripts and programs related to processes and signals in Linux. Each file serves a specific purpose as described below:

##files

1. **0-what-is-my-pid**
This script will display the Process ID (PID) of the current shell.

2. **1-list_your_processes**
A script that lists all processes currently running on the system.

3. **2-show_your_bash_pid**
A script that displays the PID of the bash shell.

4. **3-show_your_bash_pid_made_easy**
An alternative and more straightforward version of the previous script to show the PID of the bash shell.

5. **4-to_infinity_and_beyond**
A script that runs an infinite loop to keep the process busy.

6. **5-dont_stop_me_now**
This script runs a process that cannot be terminated using traditional methods.

7. **6-stop_me_if_you_can**
A script that tries to stop the process started by "5-dont_stop_me_now".

8. **7-highlander**
A script that ensures only one instance of itself can be running.

9. **8-beheaded_process**
This script kills the process with the given name.

10. **100-process_and_pid_file**
This script demonstrates how to create a process in the background and store its PID in a file.

11. **101-manage_my_process**
A script that manages a given process, allowing you to start, stop, or get its status.

12. **102-zombie.c**
A C program that creates a zombie process to demonstrate the concept.

13.  **manage_my_process**
This script indefinitely writes "I am alive!" to the file "/tmp/my_process" with a 2-second interval. It runs as a background process and continues to execute until manually stopped. The script uses sudo to gain root privileges when writing to the file, so be cautious when executing it.

