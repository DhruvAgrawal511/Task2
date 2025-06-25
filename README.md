# Task 2 – Phishing Email Analysis

## Sample Email Summary

- **From:** security-update@appleid-confirm.com
- **Subject:** Your Apple ID Has Been Locked
- **Link:** http://appleid-lockverify.com/login

---

## Phishing Indicators

| Indicator | Explanation |
|----------|-------------|
| Spoofed Domain | Appears as Apple but is actually `appleid-confirm.com` |
| Urgent Tone | Threatens account lock within 24 hours |
| Fake Link | Redirects to phishing login page |
| Header Tampering | Return-Path doesn't match sender |
| Generic Content | No personalization, overly vague language |

---

## Tools Used

- [MXToolbox Email Header Analyzer](https://mxtoolbox.com/EmailHeaders.aspx)
- Kali Linux (for safe analysis)

---

## Key Concepts

- Email Spoofing
- Social Engineering
- Phishing Detection
- Threat Indicators

---

## Header Analysis

This email failed all key authentication mechanisms (SPF, DKIM, DMARC) and showed signs of spoofing.  
See full breakdown: [header_analysis.txt](header_analysis.txt)


---

## Outcome

Learned to identify spoofed sender domains, suspicious links, and urgent social engineering language in phishing emails.
