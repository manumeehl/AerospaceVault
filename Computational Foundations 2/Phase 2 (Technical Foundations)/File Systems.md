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