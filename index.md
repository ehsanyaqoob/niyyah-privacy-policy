# Privacy Policy — Niyyah

Last updated: June 16, 2026

This Privacy Policy describes how Niyyah ("the App", "We", "Us") collects, uses, and protects your information when you use our prayer tracking application.

## Interpretation and Definitions

**Application** refers to Niyyah, the iOS prayer tracking app.  
**Company** refers to the individual developer, Muhammad Ehsan Yaqoob, Pakistan.  
**Personal Data** means any information that relates to an identified or identifiable individual.  
**You** means the individual using the Application.

---

## What Data We Collect

### Account Information
When you create an account, we collect:
- **Email address** — used for authentication only
- **Apple ID** (if you choose Sign in with Apple) — we receive only a unique identifier and optional email from Apple

We do not collect your name, phone number, payment information, or any other personal identifiers.

### Prayer Data
Your prayer logs (which prayers you prayed, missed, or marked as qaza) are stored:
- **Locally on your device** using SwiftData
- **In the cloud** via Supabase (encrypted, tied to your account) for backup and cross-device sync

This data is associated with your account and is never shared with third parties.

### Location Data
Niyyah requests your device location **only to calculate accurate prayer times** for your area. Your coordinates are:
- Used locally on-device by the Adhan library
- Never uploaded to our servers
- Never shared with any third party

Location access can be revoked at any time via iOS Settings.

### Notification Data
If you grant notification permission, Niyyah schedules local prayer time reminders. No notification data is sent to external servers.

---

## How We Use Your Data

| Purpose | Data Used |
|---|---|
| Authentication | Email or Apple ID |
| Prayer time calculation | Device location (local only) |
| Prayer log backup & sync | Prayer logs (encrypted, cloud) |
| Prayer time reminders | Local notifications only |

We do not use your data for advertising, analytics, or any commercial purpose.

---

## Data Storage and Security

Your data is stored using **Supabase**, a secure cloud infrastructure provider. All data is:
- Encrypted in transit (HTTPS/TLS)
- Protected by Row Level Security — only you can access your own data
- Stored on servers located in the EU (Supabase default region)

No method of transmission over the Internet is 100% secure, but we use commercially reasonable means to protect your data.

---

## Data Retention

We retain your account and prayer data for as long as your account is active. If you delete your account, all associated data is permanently deleted within 7 days.

---

## Deleting Your Data

### Option 1 — In-App (Coming in v1.1)
Account deletion will be available directly in Settings.

### Option 2 — Email Request
Send an email to **niyyahapp@gmail.com** with subject `Account Deletion Request`. We will process your request within 7 days and confirm deletion.

---

## Third-Party Services

Niyyah uses the following third-party services:

| Service | Purpose | Privacy Policy |
|---|---|---|
| Supabase | Authentication & cloud sync | [supabase.com/privacy](https://supabase.com/privacy) |
| Apple Sign In | Optional authentication | [apple.com/legal/privacy](https://www.apple.com/legal/privacy/) |
| Adhan (open source) | Prayer time calculation | Local only, no data sent |

---

## Children's Privacy

Niyyah is not directed at children under 13. We do not knowingly collect personal information from children under 13.

---

## Changes to This Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by updating the "Last updated" date at the top of this page. Continued use of the app after changes constitutes acceptance of the updated policy.

---

## Contact Us

If you have any questions about this Privacy Policy or want to request data deletion:

- **Email:** niyyahapp@gmail.com
- **Developer:** Ehsan Yaqoob, Islamabad, Pakistan
