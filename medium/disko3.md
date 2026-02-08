## DISCKO 3

**Category:** Forensics / Advanced Disk Analysis  
**Difficulty:** Medium  

### Problem Summary
DISCKO 3 builds upon the previous disk analysis challenges and requires a more detailed inspection of a disk image. The objective was to locate hidden or fragmented data that is not immediately visible through basic inspection.

### Approach
Having solved DISCKO 1 and DISCKO 2, I approached this challenge by first confirming the disk image type and then planning a structured analysis. Since this was a higher medium-level problem, I expected the data to be stored deeper within the disk structure.

I explored the disk image carefully, paying attention to file system details and unusual patterns. Instead of relying on a single command, I combined multiple analysis techniques to narrow down where the relevant data could be located.

By iteratively inspecting the disk contents and validating findings at each step, I was able to uncover the hidden information required to complete the challenge.

### Tools Used
- `file`
- `strings`
- `fls`
- disk image and file system analysis tools
- Linux command line utilities

### Key Learning
This challenge reinforced the importance of a systematic and patient approach in forensic analysis. It also helped me understand how data can be deliberately hidden within disk images to increase analysis complexity.

### Analysis

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/54396aa5-465d-4d3d-9092-500f222c2bc8" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/fa592d1d-b5db-473b-abf1-1802611e791c" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/cff63266-ff6f-435b-b849-6b90580e0a70" />
