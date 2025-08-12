# 🔓 Research on Common Password Attacks

## 📌 Overview
Passwords are one of the most widely used methods of authentication, but they are also frequent targets for attackers.  
This document summarizes common password attack methods and how they work.

---

## 🛠 Types of Password Attacks

### 1. **Brute Force Attack**
- **Description:** Tries every possible combination of characters until the correct password is found.
- **Speed Factors:** Depends on password length, complexity, and attacker resources (e.g., GPU speed).
- **Prevention:**
  - Use long and complex passwords.
  - Implement account lockout after multiple failed attempts.

---

### 2. **Dictionary Attack**
- **Description:** Uses a precompiled list of common words, phrases, and leaked passwords to guess credentials.
- **Prevention:**
  - Avoid dictionary words and predictable patterns.
  - Add symbols and numbers in non-obvious positions.

---

### 3. **Credential Stuffing**
- **Description:** Uses stolen username-password pairs from one breach to try logging into other services.
- **Prevention:**
  - Never reuse passwords across accounts.
  - Enable Multi-Factor Authentication (MFA).

---

### 4. **Phishing**
- **Description:** Tricks users into revealing passwords through fake login pages or malicious emails.
- **Prevention:**
  - Verify website URLs.
  - Educate users about phishing indicators.

---

### 5. **Keylogging**
- **Description:** Malicious software records keystrokes to steal entered passwords.
- **Prevention:**
  - Use updated antivirus software.
  - Avoid logging in from untrusted devices.

---

### 6. **Rainbow Table Attack**
- **Description:** Uses precomputed hashes of passwords to quickly find matches in stolen hash databases.
- **Prevention:**
  - Use salted password hashing algorithms (e.g., bcrypt, Argon2).

---

## 📚 References
- OWASP Authentication Cheat Sheet
- NIST Special Publication 800-63B
- [Have I Been Pwned](https://haveibeenpwned.com/)
