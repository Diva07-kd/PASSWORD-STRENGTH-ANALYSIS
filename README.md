# Task 6 – Password Strength Analysis

## 📌 Objective
The goal of this task was to understand what makes a password strong by testing different passwords
using online password strength checkers, and learning how complexity affects security against common attacks.

---

## 🛠 Tools Used
- [PasswordMeter.com](https://passwordmeter.com) – to measure password strength, complexity, and crack time.

---

## 📊 Test Results

| Password        | Score  | Complexity   | Length | Contains                         | Why it’s Strong/Weak |
|-----------------|--------|--------------|--------|-----------------------------------|----------------------|
| Anand@task242   | 100%   | Very Strong  | 13     | Uppercase, lowercase, numbers, symbol | Long, mixed character types, unpredictable |
| password        | 8%     | Very Weak    | 8      | Only lowercase letters            | Common word, short, no variation |

---

## 📝 Detailed Analysis

### 1. Anand@task242
- *Score:* 100%
- *Why Strong?*
  - Long enough (13 characters)
  - Mix of uppercase, lowercase, numbers, and a symbol
  - Not a common dictionary word
  - Harder for brute force and dictionary attacks

### 2. password
- *Score:* 8%
- *Why Weak?*
  - Common password used worldwide
  - All lowercase, no numbers or symbols
  - Easy target for dictionary attacks
  - Short length makes brute force attacks quick

*Key Takeaway:*  
A longer password with a mix of character types and no obvious words is far more secure than short, 
common passwords.

---

## 🔑 Key Concepts & Risk Analysis

### Password Strength
How secure a password is against different attacks. Factors include length, variety of characters, and randomness.
- *Risk:* Weak passwords can be cracked instantly, leading to account compromise.

### Brute Force Attack
Tries every possible character combination until the correct one is found.
- *Risk:* Short passwords (6–8 characters) can be cracked in seconds; longer, complex ones can take years.

### Dictionary Attack
Uses pre-made lists of common passwords and words.
- *Risk:* Common words like password or qwerty are instantly cracked.

### Authentication
Process of proving your identity when logging in (passwords, codes, biometrics).
- *Risk:* Weak authentication means an attacker only needs your password to get in.

### Best Practices
- Use *12–16+ characters*
- Mix uppercase, lowercase, numbers, and symbols
- Avoid personal details and common words
- Use passphrases (e.g., Green$Coffee!42Horse)
- Turn on *Two-Factor Authentication (2FA)*
- Store passwords in a *password manager*

---

## 📷 Screenshots
*Strong Password Example:*  
![Strong Password](screenshots/strong_password.png)

*Weak Password Example:*  
![Weak Password](screenshots/weak_password.png)

---

## 📚 What I Learned
From this activity, I learned:
- Why length and character variety are important for password security
- How common passwords are easily cracked
- The importance of using unique passwords for each account
- How tools like password meters help evaluate password strength

---
