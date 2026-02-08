## DISCKO 1

**Category:** Forensics / File Analysis  
**Difficulty:** Easy  

### Problem Summary
The challenge provided a disk image file. The objective was to analyze the disk image and locate hidden or stored data inside it to retrieve the flag.

### Approach
I first identified the type of file I was working with to confirm that it was a disk image. Since disk images often contain file systems or embedded data, I avoided treating it like a regular file.

I explored the contents of the disk image using basic analysis techniques. By inspecting the file structure and searching for readable information, I was able to locate relevant data that led to the solution.

### Tools Used
- `file`
- `strings`
- disk image inspection tools
- Linux command line

### Key Learning
This challenge helped me understand how disk images can store data and how forensics-style analysis is useful for uncovering information that is not immediately visible.

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/01380e3c-8de2-422a-8398-505f406aab64" />
![Uploading image.png…]()
