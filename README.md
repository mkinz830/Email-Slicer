# 📧 Email Username & Domain Extractor

This simple Python script extracts the **username** and **domain** from a user-provided email address.

---

## 🧾 Description

When a user enters an email address, the script separates it into two parts:
- **Username**: The portion before the `@` symbol
- **Domain**: The portion after the `@` symbol

---

## 🛠 How It Works

1. Prompts the user for their email address.
2. Locates the `@` symbol using `str.index()`.
3. Uses string slicing to extract:
   - Everything before `@` as the `username`
   - Everything after `@` as the `domain`
