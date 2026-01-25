# SHA256 Password Cracking Practice (John the Ripper)

This repository contains a **hands-on practice lab** for cracking **Raw‑SHA256** password hashes using **John the Ripper** with the **RockYou wordlist** and rules.

**Ethical Use Warning**  
These techniques are used **only for educational purposes**, such as:
- Personal learning labs
- CTF challenges
- Authorized test environments  

Never attack real systems or hashes without proper permission.

---

## Usage

```bash
git clone https://github.com/samrat-xyz/sha256_hashes-cracking.git
cd sha256_hashes-cracking
john --format=raw-sha256 --wordlist=/usr/share/wordlists/rockyou.txt --rules sha256.txt
john --format=raw-sha256 --show sha256.txt

