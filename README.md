# 🔐 Cyber Security Internship — Task 2

![Internship](https://img.shields.io/badge/Internship-Future%20Interns-blue?style=for-the-badge)
![Task](https://img.shields.io/badge/Task-2%20%7C%20Phishing%20Email%20Detection%20%26%20Awareness%20Report-red?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)
![Tools](https://img.shields.io/badge/Tools-MXToolbox%20%7C%20Google%20Admin%20Toolbox%20%7C%20Web%20Browser-orange?style=for-the-badge)

---

**Internship Program:** Cyber Security Internship by Future Interns

**Intern Name:** Kothamasu Sai Prasad

**Task-2:** Phishing Email Detection & Awareness Report

---

## 🧩 Introduction

Phishing is a social engineering attack where attackers impersonate trusted organizations to trick users into revealing sensitive information such as passwords, banking details, or OTPs. These attacks are highly effective because they exploit human trust rather than technical vulnerabilities.

---

## 🎯 Objective

- ✅ Analyze phishing email samples
- ✅ Identify phishing indicators
- ✅ Classify email risks
- ✅ Use basic security tools for validation
- ✅ Provide awareness and prevention guidelines
- ✅ Present findings in a structured report

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Google Admin Toolbox Messageheader | Email header analysis |
| MXToolbox | Domain legitimacy verification |
| Web Browser | Link and domain inspection |

---

## 📨 Email Samples

### Sample 1 — Bank Phishing Email

| Field | Details |
|---|---|
| **From** | `authenticationmail@trust.ameribank7.com` |
| **Subject** | A new login to your bank account |

**Content:**
> There has been a recent login to your account. Reset your password immediately: `https://trust.ameribank7.com/reset-password`

---

### Sample 2 — Job Scam Email

| Field | Details |
|---|---|
| **From** | `Aisha.Mansour@bot.go.tz` |
| **Subject** | Weekly Paid Job |

**Content Summary:**
> Offers a fake UNICEF job with $500 weekly payment and asks users to contact via Gmail.

---

## ⚙️ Methodology

The following steps were performed:

1. Collected phishing email samples
2. Inspected sender email addresses
3. Analyzed suspicious links and domains
4. Identified phishing indicators
5. Performed basic domain checks using tools
6. Documented findings with evidence

---

## 🔍 Email Analysis

### Email 1 — Bank Phishing

**Phishing Indicators:**
- Fake domain not associated with Bank of America
- Urgent instruction to reset password
- Suspicious link domain
- Generic greeting
- Grammar mistake ("divice")
- Fake IP address (192.168.0.1)

**Link Analysis:**
The URL `trust.ameribank7.com` is not an official banking domain and is likely created to mimic a legitimate site.

**Tool Usage:** Domain analyzed using MXToolbox to verify legitimacy.

**Risk Level:** 🔴 High — Phishing

**Attack Explanation:**
The attacker impersonates a bank and creates urgency to trick users into clicking a fake link. Once credentials are entered, the attacker gains unauthorized access.

---

### Email 2 — Job Scam

**Phishing Indicators:**
- Fake association with UNICEF
- Uses Gmail instead of an official domain
- Unrealistic job offer ($500/week)
- Generic message content
- External contact request

**Link Analysis:**
The email redirects communication to a Gmail address instead of an official organizational domain.

**Tool Usage:** Domain credibility checked using MXToolbox.

**Risk Level:** 🔴 High — Phishing / Scam

**Attack Explanation:**
The attacker uses a fake job offer to lure victims into sharing personal details or making payments.

---

## 🗂️ Evidence Collection

The following evidence was collected:
- Email screenshots (phishing samples)
- Suspicious link inspection screenshots
- Domain analysis results using MXToolbox
- Header analysis using Google Admin Toolbox Messageheader

---

## 📊 Findings Summary

| Indicator | Email 1 (Bank Phishing) | Email 2 (Job Scam) |
|---|---|---|
| Fake Domain | ✅ | ✅ |
| Urgency Tactics | ✅ | ❌ |
| Suspicious Link | ✅ | ❌ |
| Generic Content | ✅ | ✅ |
| Grammar Issues | ✅ | ❌ |
| Scam Offer | ❌ | ✅ |
| **Risk Level** | 🔴 High | 🔴 High |

---

## 💥 Impact Analysis

These phishing attacks can lead to:
- Account compromise
- Financial fraud
- Identity theft
- Unauthorized access
- Loss of sensitive information

---

## 📉 Risk Classification

| Severity | Description |
|---|---|
| 🔴 High | Confirmed phishing attack |
| 🟡 Medium | Suspicious email |
| 🟢 Low | Legitimate email |

---

## 🛡️ Prevention Guidelines

**✔ Do's**
- Verify sender email address
- Check official domains
- Hover over links before clicking
- Report suspicious emails

**❌ Don'ts**
- Don't click unknown links
- Don't share passwords or OTPs
- Don't trust urgent messages blindly
- Don't respond to fake job offers

---

## ✅ Conclusion

This report demonstrates how phishing attacks exploit trust using fake domains, urgency, and attractive offers. User awareness and careful verification are critical in preventing such attacks. This task helped develop practical skills in phishing detection and cybersecurity reporting.

---

## 📚 References

| Resource | Link |
|---|---|
| OWASP Phishing Guidelines | https://owasp.org |
| MXToolbox | https://mxtoolbox.com |
| Google Admin Toolbox | https://toolbox.googleapps.com |

---

> ⚠️ **Disclaimer:** This analysis was conducted using safe and non-intrusive techniques for educational purposes only. No real systems were targeted or harmed.

---

<div align="center">

**Made with 🔐 by Kothamasu Sai Prasad**
*Cyber Security Internship — Future Interns*

</div>
