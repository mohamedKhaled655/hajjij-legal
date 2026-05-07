<div align="left" style="font-size: 14px; margin-bottom: 24px;">
  <a href="./">← Home</a> &nbsp;·&nbsp; <a href="privacy-ar">العربية</a>
</div>

# Privacy Policy — Hajjij App

**Effective date:** 7 May 2026
**Last updated:** 7 May 2026

---

## 1. Introduction

This Privacy Policy explains how the **Hajjij** mobile application ("the App", "we", "us", or "our") collects, uses, stores, and protects your personal information. Hajjij is a field-inspection and property-compliance management app designed for authorized inspectors and operations teams.

By using the App, you consent to the data practices described in this Policy.

---

## 2. Information We Collect

We collect the following categories of data when you use the App:

### 2.1 Account Data
- **Username and password**: required to create an account and log in. Passwords are stored on our servers in **hashed form** and cannot be retrieved as plain text.
- **User ID** and **role** within the system.

### 2.2 Authentication Data
- **JWT access and refresh tokens** are stored locally on your device using **encrypted secure storage** (Android Keystore via `flutter_secure_storage`).

### 2.3 Location Data
- **Precise location (GPS Fine)** and **approximate location (Coarse)**.
- Location is requested **only while you are actively using the App (foreground only)** and only at two specific moments:
  - When recording inspection videos in the field (to verify inspector presence).
  - When submitting task reviews.
- We **do not track your location in the background** and do not maintain a continuous movement log.

### 2.4 Camera and Microphone Data
- **Photos and videos** you capture inside the App for inspection documentation.
- **Audio recording** accompanying videos when you record audio-enabled video.

### 2.5 Files and Documents
- If you upload files (PDF, images, etc.) via the in-app file picker, we store these files on our servers as part of the inspection report.

### 2.6 Device Information
- **Platform type** (Android), language, locale.
- **Firebase Cloud Messaging (FCM) token** — a device identifier used to deliver push notifications.

### 2.7 Inspection Data
- Inspection results and questionnaire responses.
- Estimated values, employee breakdowns, compliance summaries.
- Inspector signatures and any notes you input manually.

### 2.8 Network State
- We check your internet connectivity **only** to determine whether data can be transmitted to the server. We do not log or store this information.

---

## 3. How We Use Your Data

We use the data above strictly for the following purposes:

| Data | Purpose |
|---|---|
| Account & authentication | Allow you to log in and access tasks assigned to you |
| Location | Verify your physical presence when recording inspections and submitting reviews |
| Media (photos / videos / audio) | Document property condition as part of inspection reports |
| Files | Attach supporting documents to inspection reports |
| Device info & FCM token | Deliver task notifications and important alerts |
| Inspection data | Generate compliance reports and analyze properties |

We **do not** use your data for advertising or marketing, and we **do not sell** your data to any third party.

---

## 4. Legal Basis for Processing

We process your data based on:
- **Performance of an employment / contractual relationship**: your use of the App in the course of your job or contract requires the collection of this data.
- **Your explicit consent** when granting permissions for camera, location, microphone, and notifications.
- **Legal and regulatory obligations** related to the retention of inspection records.

---

## 5. Sharing With Third Parties

We share a minimum amount of data with the following parties only:

### 5.1 Google Firebase Cloud Messaging (FCM)
- **What is shared**: device FCM token and notification content (task title and summary).
- **Purpose**: deliver push notifications to your device.
- **Google's privacy policy**: <https://policies.google.com/privacy>

### 5.2 Hosting Infrastructure
- The App's servers and databases run with hosting providers we engage **inside the Kingdom of Saudi Arabia** under data-processing agreements (DPAs).

### 5.3 What We Do Not Do
- **We do not sell your data** to any third party.
- **We do not use advertising platforms** (such as Google Ads or Meta Ads).
- **We do not currently use external behavioral analytics platforms.**

---

## 6. Data Storage Location

Your account data, inspection reports, and media are stored on servers **inside the Kingdom of Saudi Arabia**, in compliance with the **Saudi Personal Data Protection Law (PDPL)** issued by the Saudi Data and AI Authority (SDAIA).

If we ever need to transfer any data outside the Kingdom (e.g., for Google FCM delivery), this is done in accordance with PDPL controls and with equivalent protective safeguards.

---

## 7. Security and Encryption

We apply technical and organizational measures to protect your data, including:
- **Encryption in transit**: all communication with our servers uses HTTPS/TLS.
- **Encryption at rest on device**: authentication tokens are stored in **Android Keystore** via `flutter_secure_storage`.
- **Password hashing**: passwords are stored on the server hashed and salted; they cannot be retrieved.
- **Access control**: access to data within our team is restricted to authorized personnel only.
- **Monitoring** for unauthorized access attempts and periodic security log reviews.

Despite the above measures, absolute security of any electronic system cannot be guaranteed. We continuously work to improve our defenses.

---

## 8. Data Retention

- We retain your data for as long as your account is active and your association with the registering organization continues.
- After an account deletion request, your data is deleted within a maximum of **30 days**.
- Some data may be retained for longer periods if required by a legal or regulatory obligation (e.g., inspection reports required by a regulatory body), in which case it is kept in **anonymized** form whenever possible.

---

## 9. Your Rights Under PDPL

You have the following rights at any time:

| Right | How to exercise it |
|---|---|
| **Access your data** | Request a copy of the data we hold about you via the contact email below |
| **Correct your data** | Contact us to correct any inaccurate information |
| **Delete your account and data** | See Section 10 |
| **Withdraw consent** | You may revoke permissions (location, camera, notifications) from your device settings at any time |
| **Object to processing** | Request that we stop processing your data for specific purposes |
| **Data portability** | Request your data in a structured, machine-readable format |
| **File a complaint** | You may file a complaint with the **Saudi Data and AI Authority (SDAIA)** at <https://sdaia.gov.sa> |

---

## 10. Account and Data Deletion

To request deletion of your account and data:

1. Send an email to **`privacy@hajjij.example`** from the **same email address associated with your account**.
2. Use the subject line: **"Account Deletion Request — [your username]"**.
3. We will verify your identity and process your request within **30 days**.
4. The following data will be deleted:
   - Personal account data (username, role, device preferences).
   - Authentication tokens and login history.
   - Photos, videos, and inspection data linked to your account.
5. **Exception**: certain records required by legal or regulatory obligations may be retained in **anonymized** form.

You will receive an email confirmation when the deletion is complete.

---

## 11. Children's Privacy

Hajjij is intended for professional/business use and is not directed at children under **18 years of age**. We do not knowingly collect data from children. If we discover that we have collected data from a child, we will delete it promptly.

---

## 12. Changes to This Policy

We may update this Policy from time to time to reflect changes in our practices or legal requirements. When we make material changes:
- We will publish the updated Policy at the same URL with a new **Effective date**.
- We will notify you via in-app notice or email at least **30 days** before the change takes effect.

Your continued use of the App after the update constitutes acceptance of the new Policy.

---

## 13. Contact Us

For any inquiries or requests related to this Policy or your data:

- **Privacy email**: `privacy@hajjij.example`
- **Subject line format**: For fastest handling, use: `Privacy Inquiry — [request type]`

We respond to all inquiries within a maximum of **10 business days**.

---

*Hajjij. Privacy Policy, version 1.0.*
