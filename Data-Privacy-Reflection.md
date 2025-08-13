# Data Privacy & Confidentiality – Reflection

## 🔍 Key Learnings

### What Types of Data Are Confidential at Focus Bear?

- Identification, Social, Academic & Professional, Commercial & Marketing, Technical, Economic & Financial & Insurance, Profile, Aggregate, Special Category of Personal

### Best Practices for Handling Data

- Use **encrypted storage** (e.g., password-protected devices and drives).
- Keep sensitive data **out of code repositories** (no API keys or tokens in GitHub).
- Share documents only with **authorized team members** through secure channels.
- Log out of shared systems when not in use.

### How to Respond to a Data Breach

1. Immediately report the issue to the team lead or security contact.
2. Revoke access or credentials if necessary.
3. Help document what happened and suggest ways to prevent it in the future.

---

## 📝 Reflection

### Steps I Will Take to Handle Data Securely

As a **Mobile App Developer**, I will:
- Double-check that no API keys or credentials are committed to GitHub.
- Use `.env` files to store environment variables locally.
- Use strong, unique passwords with 2FA enabled on all accounts.
- Keep devices locked and encrypted when not in use.

### How I’ll Store, Share, and Dispose of Data

- **Store**: Use secure cloud services or encrypted folders.
- **Share**: Use Slack or other company-approved tools only with authorized people.
- **Dispose**: Regularly clean up old data/files and empty trash securely.

### Common Mistake to Avoid

A common mistake is **pushing secrets to public repos**. I will:
- Use `.gitignore` to prevent committing `.env` files
- Regularly audit my repos to check for exposed sensitive info

---

## 🛠️ Task Summary

### One Practice I Will Adopt

I will start using **Focus Bear reminders** to perform a weekly check of my local and GitHub repos to ensure no sensitive data is accidentally exposed.

### One Key Learning

**Never commit secrets into version control.**  
Even a temporary leak can be captured and misused. Instead, always use `.env` files and secret managers.

---
