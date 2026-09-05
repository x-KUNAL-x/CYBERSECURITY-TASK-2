# Phishing Email Analysis Report

## 1. Introduction

This report analyzes a sample email to identify common phishing indicators. The analysis focuses on the sender's address, suspicious links, urgency tactics, display-name mismatches, attachments, and email header information.

The purpose of this analysis is to understand how phishing emails attempt to trick users into revealing sensitive information such as usernames, passwords, and account details.

---

## 2. Sender's Address

The email appears to come from **PayPal**, but the sender's email address is:

`security@paypal.alerts-fake.com`

This is **not an official PayPal domain**. The use of a suspicious domain that attempts to resemble a trusted organization is a strong indicator of phishing.

**Finding:** 🚨 Suspicious sender domain

---

## 3. Spelling and Grammar

The email uses mostly correct spelling and grammar. However, the message uses overly formal and generic language such as:

> "Dear John"

The lack of genuine personalization can be a warning sign, especially when combined with other suspicious characteristics.

**Finding:** ⚠️ Generic communication style

---

## 4. Suspicious Links

The email contains a button labeled:

**"Verify your identity now"**

When the link is inspected, it points to:

`http://pay-pal-fake-login.com`

The link does not use the official PayPal domain and appears designed to imitate a legitimate login page.

**Finding:** 🚨 Suspicious/fake URL

This type of link may be used to steal usernames, passwords, payment information, or other sensitive data.

---

## 5. Urgent Language

The email creates a sense of urgency using statements such as:

* "Log into PayPal to verify your identity..."
* "You won't be able to send or withdraw money..."
* "Please do not reply to this email."

Threats of account restrictions or loss of access are commonly used in phishing attacks to pressure users into acting without verifying the message.

**Finding:** 🚨 Urgency and pressure tactics

---

## 6. Display Name and Email Mismatch

The sender's display name appears as:

**PayPal Security**

However, the underlying email address is:

`security@paypal.alerts-fake.com`

The display name suggests a legitimate PayPal security department, while the actual domain is unrelated to the official PayPal domain.

**Finding:** 🚨 Display-name and email-domain mismatch

---

## 7. Attachment Analysis

There is **no attachment in this specific sample**.

However, phishing emails may contain dangerous attachments such as:

* `.exe`
* `.zip`
* `.scr`
* `.js`
* Macro-enabled Office documents

Users should avoid opening unexpected attachments, especially when they are accompanied by urgent requests.

**Finding:** ✅ No attachment detected in this sample

---

## 8. Email Header Analysis

Email headers can provide additional information about the actual origin of an email.

A header-analysis service such as MXToolbox can be used to examine information including:

* Sender IP address
* Mail servers
* Received headers
* Return-Path
* Message-ID
* Sending infrastructure

For a real investigation, the complete original email headers should be analyzed to verify whether the message originated from legitimate infrastructure.

**Finding:** ⚠️ Header analysis should be used to verify the sender's actual origin.

> **Note:** The sample information provided for this report does not include the original full email headers, so the header findings should not be treated as independently verified.

---

## 9. Phishing Indicators Summary

| Indicator                | Observation                                         | Risk      |
| ------------------------ | --------------------------------------------------- | --------- |
| 🧑‍✉️ Sender Address     | `alerts-fake.com` is not the official PayPal domain | 🔴 High   |
| 🧠 Spelling/Grammar      | Mostly correct, but generic language is used        | 🟡 Medium |
| 🔗 Suspicious Link       | Points to `pay-pal-fake-login.com`                  | 🔴 High   |
| ⚠️ Urgent Language       | Warns about losing account functionality            | 🔴 High   |
| 🔁 Display Name Mismatch | "PayPal Security" vs. fake domain                   | 🔴 High   |
| 📎 Attachment            | No attachment in this sample                        | 🟢 Low    |
| 🧾 Header Analysis       | Requires original email headers for verification    | 🟡 Medium |

---

## 10. Recommended Safety Measures

To protect against phishing emails:

1. Do not click suspicious links.
2. Do not enter passwords or financial information through email links.
3. Check the sender's complete email address.
4. Hover over links before clicking them.
5. Be suspicious of urgent account warnings.
6. Do not open unexpected attachments.
7. Verify suspicious messages through the organization's official website or application.
8. Use email security and spam filters.
9. Report suspected phishing emails to the appropriate organization or security team.

---

## 11. Final Conclusion

Based on the indicators identified in the sample, the email should be treated as a **phishing attempt**.

The major red flags include:

* Fake sender domain
* Suspicious login URL
* PayPal display-name mismatch
* Urgent account-related warnings
* Attempt to direct the user toward identity verification

These techniques are commonly used by attackers to create trust and urgency and to trick users into revealing sensitive information.

**Security Recommendation:** Never enter credentials or personal information through a suspicious email link. Instead, independently navigate to the organization's official website or application.

---

## 12. Disclaimer

This report is created for **educational and cybersecurity awareness purposes**. The email addresses, domains, and examples used in this sample analysis should be treated as demonstration data and not as evidence of a real-world attack.

No unauthorized access, credential collection, or malicious activity was performed during this analysis.
