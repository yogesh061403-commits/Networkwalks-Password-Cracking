
## Password Cracking | NetworkWalks Week 3

Hands-on password-cracking exercises using John the Ripper, Johnny GUI, and NetworkWalks online tools.

## About This Project

As part of Week 3 of my NetworkWalks Cybersecurity Internship, I completed two practical modules focused on password cracking.

The project involved extracting hashes from password-protected PDF files, performing password-cracking operations using different tools, and verifying the recovered passwords.

## Project Modules

| Module | Project Name | Tools Used |
|--------|---------------|------------|
| PM1 | Password Cracking with JTR | John the Ripper & Johnny |
| PM2 | Password Cracking with NetworkWalks Tools | Hash Calculator & Password Cracker |

## PM1 - Password Cracking with John the Ripper

### Objective
Recover passwords from password-protected PDF files using John the Ripper and Johnny GUI.

### Tools Used
- John the Ripper (JTR)
- Johnny GUI
- Online PDF Hash Extractor
- PDF Reader

### Practical Steps
1. Downloaded and configured John the Ripper and Johnny GUI.
2. Extracted the hash from each password-protected PDF using an online PDF hash extractor.
3. Saved each extracted hash and loaded it into Johnny.
4. Started the password-cracking attack for each PDF.
5. Recovered the passwords and verified them by opening the protected PDF files.

### Screenshots & Evidence

**PDF 1**

1. Hash Extraction

[MyLockedPDF1 Hash](screenshots/PM1-JTR/hash1.jpg)

2. Password Cracked using Johnny (password: `password1`)

![PDF1 Johnny Result](screenshots/PM1-JTR/findpass1.jpg)

3. Password Verified — Flag Captured

[PDF1 Flag Captured](screenshots/PM1-JTR/locked1.jpg)

**PDF 2**

4. Hash Extraction

[PDF2 Hash](screenshots/PM1-JTR/hash2.jpg)

5. Password Cracked using Johnny (password: `good-luck`)

[PDF2 Johnny Result](screenshots/PM1-JTR/findpass2.jpg)

6. Password Verified — Flag Captured

[PDF2 Flag Captured](screenshots/PM1-JTR/locked2.jpg)

### Result
Successfully performed password cracking on both protected PDF files using John the Ripper through Johnny GUI.

## PM2 - Password Cracking with NetworkWalks Tools

### Objective
Recover the passwords of protected PDF files using the NetworkWalks Hash Calculator and Password Cracker.

### Tools Used
- NetworkWalks Hash Calculator
- NetworkWalks Password Cracker
- Web Browser
- PDF Reader

### Practical Steps
1. Uploaded each password-protected PDF to the NetworkWalks Hash Calculator.
2. Extracted and copied the generated PDF hash.
3. Submitted the hash to the NetworkWalks Password Cracker.
4. Ran the dictionary attack until the password was found.
5. Verified the password by opening the protected PDF.
6. Captured the completion flag.

### Screenshots & Evidence

**PDF (1st file)**

1. Hash Extraction

[Hash Calculator Result](screenshots/PM2-NW/PM2hash1.jpg)

2. Password Cracked (password: `password1`)

[Password Cracker Result](screenshots/PM2-NW/PM2findpass3.jpg)

3. Flag Captured

[Flag Captured](screenshots/PM2-NW/unlock1.jpg)

**PDF (2nd file)**

4. Hash Extraction

[Hash Calculator Result](screenshots/PM2-NW/PM2hash2.jpg)

5. Password Cracked (password: `1qaz2wsx`)

[Password Cracker Result](screenshots/PM2-NW/PM2findpass4.jpg)

6. Flag Captured

[Flag Captured](screenshots/PM2-NW/unlock2.jpg)

### Result
Successfully recovered both PDF passwords and captured the completion flags using NetworkWalks online tools.

## Key Learnings

Through these practical exercises, I gained experience in:

- Extracting password hashes from protected PDF files.
- Working with John the Ripper and Johnny GUI.
- Understanding the password-cracking process using dictionary attacks.
- Using online hash extraction and calculation tools.
- Performing password cracking with NetworkWalks tools.
- Verifying recovered passwords.
- Understanding the importance of strong password protection.

## Conclusion

Working on both modules gave me practical exposure to different password-cracking tools and techniques. It was interesting to perform the same type of security exercise using both locally configured tools and browser-based tools.

These exercises helped me understand how password security can be tested and why strong passwords matter.

## Internship Details
- **Organization:** NetworkWalks
- **Program:** Cybersecurity & Ethical Hacking Internship
- **Week:** 03
- **Project:** Password Cracking
- **Modules:** Project Module 1 & Project Module 2

##

*All practical activities were performed as part of an authorized cybersecurity training exercise.*
EOF

