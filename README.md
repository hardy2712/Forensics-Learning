# Forensics Artifacts

Amchache Parser -> it will be used in sharing the recent execution of data which will store the cache of all what has run and what has came in machine it stores the SHA-1 , parent version 


**Execution Flags**: AMCache records execution flags for programs, which indicate the compatibility settings applied during execution. These flags provide information about how the program was run, such as compatibility mode, administrator privileges, or other settings.



**File Sizes:** AMCache includes information about the sizes of executed files. This data can help identify suspicious or unusual file sizes associated with executed programs.

**SHA-1 Hashes:** AMCache stores SHA-1 hashes of executed files. These hashes can be used for file identification and integrity verification.

**Execution Count:** AMCache keeps track of how many times a particular program has been executed. This data can indicate the frequency of program usage and highlight commonly used applications.

**First and Last Execution Timestamps:** AMCache records the timestamps of the first and last execution of a program. These timestamps can help establish the time range during which a program was active on the system.

**User-Specific Data:** AMCache differentiates between user-specific installations and executions, allowing investigators to determine which programs were installed or executed by specific users on a multi-user system.

**Volume Information:** AMCache provides volume information for executed files, including the volume serial number and the file system type on which the file resides. This data can aid in tracking file movements across different volumes or devices.
