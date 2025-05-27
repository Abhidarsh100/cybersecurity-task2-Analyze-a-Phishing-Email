# 🛡️ Cybersecurity Task 2 – Analyze a Phishing Email

## 📌 Internship Task Objective
The goal of this task is to identify phishing characteristics in a suspicious email and improve email threat detection skills. This task involved analyzing a sample email to detect social engineering techniques and technical anomalies.

---

## 📧 Sample Phishing Email Overview

- **Subject:** Microsoft account password change
- **Sender:** support@msupdate.net
- **Target:** ethan@hooksecurity.co
- **Claimed Brand:** Microsoft
- **Attached File:** Microsoft-Phishing_email.png

---

## 🔍 Step-by-Step Phishing Analysis

### 1. 🕵️ Spoofed Email Domain
- The sender uses `support@msupdate.net`, which is **not an official Microsoft domain**.
- Legitimate Microsoft emails come from domains like `@microsoft.com`.

### 2. 🧾 Header Analysis .
  - [MXToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
  - [Google Admin Toolbox Message Header Analyzer](https://toolbox.googleapps.com/apps/messageheader/)

### 3. 🔗 Suspicious Links (Clickbait Techniques)
- The email includes links like:
  - Reset your password
  - Review your security info
  - Learn how to make your account more secure
- These are **classic phishing triggers**—hovering on such links (not shown in image) usually reveals **malicious redirections**.

### 4. ⚠️ Urgent Language / Fear Tactics
- Statements like “If this wasn't you, your account has been compromised” create **urgency and fear**, pushing users to act quickly.

### 5. ❗ No Microsoft Branding or Secure Footer
- The email lacks:
  - Microsoft logo
  - Legitimate branding
  - Official signature or contact information
  - Verified footer with terms or policy

### 6. 🧠 Summary of Identified Phishing Traits

| Indicator                        | Description |
|----------------------------------|-------------|
| ❌ Spoofed sender domain         | msupdate.net pretends to be Microsoft |
| ⚠️ Urgent language               | "Your account has been compromised" |
| 🔗 Potentially malicious links   | Text and CTA (Call-To-Actions) could lead to phishing websites |
| 🚫 Missing official branding     | No Microsoft logos or verification |
| 📍 Misleading IP data            | Shown to build trust, but can be faked |
| 📬 Generic signature             | Just "The Microsoft account team" |

---

## 🛠 Tools Used

- Manual inspection of sender email and message body
- [ipinfo.io](https://ipinfo.io/) (for IP address lookup)
- Email header analyzers

---

## 📁 Files Included

- `Microsoft-Phishing_email.png` – Screenshot of the phishing email
- `README.md` – This analysis report

---

## 🎯 Learning Outcomes

- Gained awareness of common phishing techniques
- Learned to identify spoofed email domains and urgency-based manipulation
- Practiced analyzing phishing content using basic threat analysis methodology

---




