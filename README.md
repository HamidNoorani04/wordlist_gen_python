# 🔐 Brute-Force Wordlist Generator – By Abdul Hamid Noorani

This Python script generates a massive custom wordlist for brute-force attacks, password auditing, and red teaming. It mixes common passwords, tech terms, pet names, cultural keywords, and **custom names** with randomized digits, uppercase letters, and symbols to create millions of password-like entries.

> ⚠️ **Strictly for educational and authorized security testing.**

---

## 📜 Features

- Generates up to **10 million** unique wordlist entries
- Supports **custom base words** (e.g., names, terms, patterns)
- Adds random **prefixes/suffixes** with digits, uppercase letters, and `@`
- Limits length to 8–12 characters (typical password policy range)
- Outputs to a `.txt` file ready for tools like Hydra, Burp, John, etc.

---

## ⚙️ Settings

- **Base words**: Mix of common passwords, patterns, names, and keywords
- **Character pool**: Uppercase A–Z, 0–9, and `@`
- **Output file**: `brute-force_wordlist_generated_by_hamid.txt`
- **Total entries**: 10,000,000

---

## 🚀 How to Use

1. Install Python 3.x  
2. Save the script as `wordlist_generator.py`
3. Run it:

```bash
python wordlist_generator.py
The script will generate and save the wordlist file in the same folder.

📂 Sample Output

@Buddy58
RAZA492
savani99@
Max01@
Wifi1234
123Hussein@

```

## 🧠 Use Cases
- **Password spraying**

- **Brute-force login testing**

- **Wordlist enhancement for bug bounty**

- **Dictionary attacks in tools like Hydra, Medusa, or Burp Suite**

>⚠️ **Disclaimer
This tool is for educational and authorized penetration testing only.
Do not use it on systems or accounts you do not have permission to access.
Unauthorized use is illegal and unethical.**

---

## 👨‍💻 Author
- **Abdul Hamid Noorani
Python Developer & Security Researcher**
