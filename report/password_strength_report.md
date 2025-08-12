# 📊 Password Strength Evaluation Report

## 🔍 Overview
This report documents the results of testing four different passwords using **Password Meter**.  
The goal was to understand how password length, complexity, and character variety affect the overall score and security rating.

---

## 🧪 Test Results

| Password Example          | Score  | Complexity   | Key Strengths                                  | Key Weaknesses                              |
|---------------------------|--------|--------------|------------------------------------------------|----------------------------------------------|
| `583644`                  | 14%    | Very Weak    | Contains numbers                               | Too short, only numbers, sequential numbers  |
| `PassWord123`             | 79%    | Strong       | Good length, uppercase + lowercase + numbers  | No symbols, consecutive lowercase letters    |
| `ZM2lRcly42Egk3P`         | 100%   | Very Strong  | Long length, mixed case, numbers, well balanced| No symbols, some repeated characters         |
| `{nr66igRP,Y37]75[b`      | 100%   | Very Strong  | Long length, mixed case, numbers, symbols     | Minor repeated characters, some consecutive numbers |

---

## 📈 Observations
1. **Length Matters** – Passwords longer than 12 characters significantly improve the score.
2. **Character Variety is Key** – Using uppercase, lowercase, numbers, and symbols together yields higher scores.
3. **Avoid Predictability** – Passwords with sequential or repeated characters lose points.
4. **Symbols Boost Security** – Adding symbols greatly improves strength and makes brute-force attacks harder.
5. **Numbers Alone are Weak** – Even if long, number-only passwords are vulnerable to dictionary and brute force attacks.

---

## 💡 Recommendations for Strong Passwords
- Use at least **12–16 characters**.
- Combine **uppercase, lowercase, numbers, and symbols**.
- Avoid common words, dictionary terms, or predictable substitutions.
- Place numbers and symbols in **non-obvious positions**.
- Avoid **sequences** like `1234` or `abcd` and repeated characters.

---

## 📚 Conclusion
Passwords with maximum character diversity, no predictable patterns, and longer length received the highest scores.  
**Best performers**:  
- `ZM2lRcly42Egk3P` (100%) — Very strong, though could be improved by adding symbols.  
- `{nr66igRP,Y37]75[b` (100%) — Excellent complexity with all character types.

**Worst performer**:  
- `583644` (14%) — Short, only numeric, predictable pattern.

By following the recommended practices above, users can create secure passwords resistant to brute force and dictionary attacks.
