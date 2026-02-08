## Corrupted File

**Category:** File Analysis / Forensics  
**Difficulty:** Easy  

### Problem Summary
The challenge provided a file that appeared to be corrupted and could not be opened normally. The objective was to analyze the file, identify what was wrong with it, and restore it to access the hidden information.

### Approach
I first examined the file to understand its actual format instead of trusting the file extension. Since corrupted files often have damaged headers or incorrect signatures, I focused on inspecting the raw file data.

By comparing the file’s structure with a valid format and correcting the necessary parts, I was able to fix the file enough to view its contents. Once the file was restored, the hidden information became accessible.

### Tools Used
- `file`
- `xxd`
- hex-level inspection
- Linux command line utilities

### Key Learning
This challenge helped me understand how file headers work and how even small changes in a file’s structure can make it unreadable. It also showed how hex-level analysis can be used to recover corrupted data.
