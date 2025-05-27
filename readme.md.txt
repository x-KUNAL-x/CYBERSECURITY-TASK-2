## Phishing Email Analysis - Sample Report

### 1. Sender's Address:

The email appears to come from "PayPal," but the sender's email is `security@paypal.alerts-fake.com`, which is **not an official PayPal domain**. This is a strong indicator of email spoofing.

### 2. Spelling/Grammar Issues:

Although the email uses mostly correct grammar, phishing emails often try to sound official. However, overly formal or generic language such as "Dear John" and missing personalization are red flags.

### 3. Suspicious Links:

The email contains a button labeled "Verify your identity now" that, when hovered over, points to `http://pay-pal-fake-login.com` instead of the official PayPal domain. This is a clear phishing attempt to steal login credentials.

### 4. Urgent Language:

The email creates a **sense of urgency** with statements like:

* "Log into PayPal to verify your identity..."
* "You won't be able to send or withdraw money..."
* "Please do not reply to this email."
  This pressure tactic is common in phishing scams.

### 5. Mismatched Display Name:

The display name shows as "PayPal Security," but the underlying email address is `alerts-fake.com`, not `paypal.com`. This mismatch is suspicious and likely fraudulent.

### 6. Attachment:

There is no attachment in this specific sample, but phishing emails sometimes contain malicious files like `.zip` or `.exe` to install malware.

### 7. Header Analysis:

Using an email header analyzer tool like [mxtoolbox](https://mxtoolbox.com/EmailHeaders.aspx), the sender's IP address and origin do not match PayPal's servers. This confirms the email is **not from the real PayPal infrastructure**.

### Final Conclusion:

This is a **phishing email** that uses fake branding, urgent warnings, and misleading links to **trick the user into giving away personal information**. Never click suspicious links or enter credentials unless you are sure the email is legitimate.
