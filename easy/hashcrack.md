## Hashcrack

**Category:** Cryptography  
**Difficulty:** Easy  

### Problem Summary
The challenge provided a hashed value and required identifying the hash type and recovering the original plaintext value.

### Approach
I first analyzed the hash length and format to narrow down the possible hashing algorithms. Based on its characteristics, I was able to identify the likely hash type.

Once the hash type was known, I attempted to crack it using commonly used wordlists and basic cracking techniques. Since the challenge was marked as easy, the plaintext was found without requiring advanced brute-force methods.

### Tools Used
- `hashid`
- `john-the-ripper`
- online hash identification references
- basic wordlist-based cracking

### Key Learning
This challenge helped me understand how hash formats can be identified by length and structure and how weak or common passwords can be cracked easily if proper security practices are not followed.

### Analysis
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/32f0b285-5e71-47eb-a696-163599a52bad" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/36b2f71b-438a-4657-a3b0-d5ae581e7dc7" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/f6d0b305-4239-4c45-8650-359510d04fcf" />

