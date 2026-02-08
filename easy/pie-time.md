## PIE Time

**Category:** Binary Exploitation / Linux  
**Difficulty:** Easy  

### Problem Summary
The challenge provided a compiled binary file. The task was to inspect the binary and find the flag hidden inside it without modifying the program.

### Approach
I first checked the file type to understand what kind of binary it was. Since the challenge name hinted towards PIE (Position Independent Executable), I explored the binary instead of directly trying to execute it blindly.
Using basic Linux analysis tools, I searched for readable strings inside the binary. 
After inspecting the output, I was able to locate the flag embedded within the binary.

### Tools Used
- `file`
- `strings`
- `objdump`
- Linux command line

### Key Learning
This challenge helped me understand that many binaries can be analyzed statically and that tools like `strings` are very useful before attempting any advanced exploitation.


### PIE-Time Analysis
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/5975f933-2dce-4e04-be8e-70c17c1d8d89" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/70a7954a-414f-49c0-ade5-6b7a111260c1" />

