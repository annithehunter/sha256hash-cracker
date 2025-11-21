# 🔐 SHA-256 Hash Cracker (Brute Force using rockyou.txt)

This project is a **Python-based SHA-256 hash cracking tool** that attempts to recover plaintext passwords by brute-forcing them using the popular **rockyou.txt** wordlist.

It is designed for **cybersecurity learning**, **ethical hacking practice**, and understanding how hashing + wordlists work in password cracking.

> ⚠️ **Disclaimer:**  
> This tool is for educational and legal penetration-testing purposes *only*.  
> Never use it on systems you don’t own or have permission to test.

---

## 🚀 Features
- Uses **rockyou.txt** wordlist for high-volume brute force attempts  
- Compares each candidate password with the target **SHA-256 hash**  
- Simple and beginner-friendly Python implementation  
- Shows which password successfully matches the hash  

---

## 🛠️ How It Works
1. Load the SHA-256 hash you want to crack  
2. Load the rockyou.txt wordlist  
3. Iterate through each password  
4. Hash each password using Python’s `hashlib`  
5. Compare with the target hash  
6. Return the cracked password if matched  

---

## 🧑‍💻 Author
**Aniruddh Kumar Yadav (@annithehunter)**  
Cybersecurity & Web Development Enthusiast

Feel free to ⭐ star the repo if you like it!
