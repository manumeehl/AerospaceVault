##### Memory vs. Persistent Storage
- Memory is byte-addressable large block of storage
-  Information in main memory is lost after power off
- Persistent storage preserves data even after reboot

Typical storage devices:
- Hard Disk Drive (HDD)
- CD-ROM (CD)
- Digital Versatile Disk (DVD)
- Universal Serial Bus (USB)

---
##### Windows vs. Unix file systems
Windows:
- 1 main storage device
- 1 Volume for each partition
- Identified by a Drive Letter

Unix:
- Each storage device is a block in the kernel
- Mounting brings them into the global directory key
- Device files are located in /dev

---
##### Absolute vs. relative Paths
Absolute Path:
- Full path to a file starting from the current directory
- No assumption about current location necessary
Relative Path:
- Refers to a location relative of the current working directory

---
##### Important command-line commands:
| Description               | Unix       | Windows |
| ------------------------- | ---------- | ------- |
| Get current path name     | pwd        | pwd     |
| change directory          | cd         | cd      |
| list content of directory | ls         | dir     |
| create a new file         | touch      | echo    |
| create a new directory    | mkdir      | mkdir   |
| move file/directory       | mv         | mv      |
| remove file/directory     | rm / rmdir | del     |
| copy file/directory       | cp         | cp      |

---
##### Life cycles of files
1. Create
2. Open 
3. Read
4. Seek
5. Write
6. Close
7. Sync

Deleting files is __not__ part of the C++ standard file API!

---
##### File Streams
- Generally, a *Stream* is a sequence of bytes
- In C++ however, a *Stream* is a flow of characters
- A file stream is the continued reading/writing process from/to a file

---

Visibility and Scopes in UML-Diagrams
Public
- Accessible by all classes and objects
- Can read, write and invoke behavior
Protected
- Accessible by derived classes
- Can read, write and invoke inside the class hierarchy
Private
- Accessible only within the same class or object
- restricted to internal read, write and invoke behavior