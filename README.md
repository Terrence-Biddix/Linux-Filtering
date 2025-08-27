# Linux-Filtering

## Objective

The objective of this lab was to practice using the grep command and piping to efficiently search for files and extract specific information from within log and user data files. This exercise demonstrated how security analysts can quickly locate critical information in system files and directories.

### Skills Learned

- Navigating Linux file system directories

- Using grep to search for specific strings within files

- Piping command output into grep for efficient filtering

- Identifying error messages in server logs

- Finding files with specific naming conventions

- Extracting and reporting user account changes

### Tools Used

- Linux Command Line

- grep

- Piping (|)

## Steps
##### Task 1. Search for error messages in a log file

Navigate to the /home/analyst/logs directory and use grep to search for error messages in the server_logs.txt file.
There were six entries in the server_logs.txt file containing the string error.

*Ref 1: Example of grep returning error entries from server logs*
<img width="696" height="187" alt="Linux 2" src="https://github.com/user-attachments/assets/9098c033-6a45-46db-a795-8ec77b6484d8" />

##### Task 2. Find files containing specific strings

Navigate to the /home/analyst/reports/users directory and use grep with pipes to filter file names.

*Ref 2: Output of grep filtering filenames with Q1 and access*
<img width="763" height="236" alt="Linux 3" src="https://github.com/user-attachments/assets/69cd29dc-8d11-4d9d-a9f5-a55c785b3379" />

Three files contained Q1 in their names.

<img width="589" height="89" alt="Linux 4" src="https://github.com/user-attachments/assets/8951fd53-ee1b-46e0-87d1-2c393a82a206" />


##### Task 3. Search file contents for user information

List files in the /home/analyst/reports/users directory:

*Ref 3: Example of grep returning user details from reports*

<img width="676" height="225" alt="Linux 4 part 2" src="https://github.com/user-attachments/assets/d7b6dc41-7089-485c-8996-de6b2916d496" />

Search the Q2_deleted_users.txt file for user jhill:
The user jhill was found in the deleted users file.

Search the Q4_added_users.txt file for users in the Human Resources department:
Two new users were added to Human Resources in Quarter 4.

<img width="879" height="293" alt="Linux 6" src="https://github.com/user-attachments/assets/a28cd5c2-5322-42d5-bce4-ee2a547f1ac0" />


## Summary

This lab provided hands-on practice with the grep command and piping, covering how to:

- Search for specific information within files

- Filter lists of files by name patterns

- Extract user account changes from system records

By completing this activity, I gained foundational Linux skills essential for cybersecurity analysis and incident response.





