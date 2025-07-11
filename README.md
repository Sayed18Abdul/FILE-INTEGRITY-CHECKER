# FILE-INTEGRITY-CHECKER
*COMAPANY* : CODTECH IT SOLUTIONS

*NAME* : SAYED ABDUL

*INTERN ID* : CT04DG3162

*DOMAIN* : Cyber Security & Ethical Hacking

*DURATION* : 4 WEEKS

*MENTOR* : NEELA SANTOSH
## DESCRIPTION:
This tool is designed to monitor changes in files by calculating and comparing their hash values. The main purpose of this tool is to detect any modifications, additions, or deletions in files over time by comparing their hash values, which are unique strings generated based on the file contents. Hash values serve as fingerprints for files, ensuring a fast and reliable way to detect changes without needing to compare the entire content of the files.
# TOOLS AND LIBRARIES USED:
1. Python :Programming language used
2. hashlib (Standard Library) :To compute and secure hash values for files
3. os (Standard Library) :To navigate the file system, walk through directories, and build paths
4. json (Standard Library) :To save and load file hash snapshots in a human readable format
# KEY FEATURES:
1.Hash Calculation:
The tool generates hash values (e.g., SHA-256 or MD5) for each file in a given directory or multiple directories. The hash is calculated using the file's content, ensuring that any change in the file (even the smallest modification) will result in a different hash value.

2.File Monitoring:
The tool continuously monitors the specified files or directories for any changes, additions, or deletions. It performs a comparison of the current hash values with previously stored values to detect modifications.

3.Change Detection:
If the hash value of a file changes, the tool flags it as modified. New files will be detected by the absence of a previously stored hash. Deleted files will be flagged if their hash value is no longer present.

4.Efficient Storage and Reporting:
The tool can store hash values of files in a database or file for easy reference and comparison. It generates logs or reports detailing the files that have changed, been added, or deleted, along with timestamps for each event.

5.Customization:
Users can choose specific directories to monitor. It can be configured to run periodically or in real-time, depending on system resources and user preference. Various hash algorithms (e.g., MD5, SHA-1, SHA-256) can be selected based on the level of security and performance desired.

6.Security & Integrity:
Hashing ensures that file integrity is maintained, and unauthorized modifications can be easily detected. It can be used in scenarios where maintaining the integrity of critical files is important, such as system files, configuration files, and security logs.

7.Performance Considerations:
The tool operates efficiently by focusing only on files whose hashes have changed, instead of scanning and comparing full file contents. It can handle large file systems and be scaled for use in enterprise environments, with options for logging and alerting users when changes occur.

# USE CASES:
1.System Administrators: To monitor the integrity of system configuration files and critical data.

2.Developers: To track changes in source code files or documentation in a project.

3.Security Professionals: To detect any unauthorized changes to sensitive files or configurations, ensuring that file integrity is maintained.

4.Backup Solutions: To verify the integrity of backup files by comparing their hashes against known good versions.
# OUTPUT
![Screenshot 2025-07-06 103336](https://github.com/user-attachments/assets/5dc54aae-5bef-439d-9fd9-648bdcfbac00)

