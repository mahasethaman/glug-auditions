## Hidden in Plainsight

**Category:** Forenic 
**Difficulty:** Easy  

### Problem Summary
The challenge provided a JPG image that appeared normal at first glance. The objective was to inspect the file closely and uncover any hidden data stored inside it.

### Approach
I started by examining the image beyond just opening it visually. Since steganography challenges often hide information within the file structure or metadata, I used basic file analysis techniques.

Using tools like `strings`, I searched for readable content that should not normally appear inside an image file. This revealed suspicious data, which hinted towards encoded information. After further inspection and decoding, I was able to extract the required information.

### Tools Used
- `file`
- `strings`
- `xxd`
- `base64`

### Key Learning
This challenge taught me that files can contain much more data than what is visible to the user and that simple command-line tools are often enough to uncover hidden information.
### Analysis
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/d88dd153-2728-4d32-9429-779787daff34" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/b5f03aff-036e-4cde-a3c3-f0250e2cfea6" />
