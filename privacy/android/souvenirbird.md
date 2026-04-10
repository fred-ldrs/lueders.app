---
title: Privacy Policy – SouvenirBird (Android)
layout: default
---

# Privacy Policy – SouvenirBird (Android)

**Responsible Party**  
Frederik Lüders  
lueders.app  
Email: hello@lueders.app

---

## 1. General Information
SouvenirBird's core is a **fully offline app** that processes only data you enter yourself. All data is stored **exclusively on your device** in a local SQLite database.

The optional **SouvenirBird Plus** subscription adds cloud features (Google Drive Sync, AI voice transcription, AI text polish) that involve internet communication and third-party services as described below.

There are no analytics, no advertising, and no tracking technologies.

---

## 2. Data Processed by the App

### Without SouvenirBird Plus (offline mode)
SouvenirBird processes only the data you voluntarily enter:

- Children's names  
- Personal souvenir notes and memories  

**Not collected:** No photos, no location data, no health data, no usage profiles.  
All data remains **on your device** and is never transmitted to any server or external service.

### With SouvenirBird Plus (optional cloud features)
If you activate SouvenirBird Plus, the following additional data may be processed:

**Google Drive Sync:** Your Google account is used for authentication (Google Sign‑In) and your souvenir data is stored in your own Google Drive.

**Whisper voice transcription:** Audio recordings you initiate are sent via HTTPS to a Cloudflare Worker proxy, which forwards them to OpenAI for transcription.

**AI text polish:** Text snippets you submit are sent via HTTPS to a Cloudflare Worker proxy, which forwards them to OpenAI (GPT‑4o‑mini) for grammar and style improvement.

All Plus features are opt-in and can be disabled in the app settings.

---

## 3. Purpose of Data Processing
The data you enter is used solely to:

- Store your personal memories locally  
- Display your souvenirs within the app  

No other processing takes place.

---

## 4. Storage & Security

**Without Plus:** All data is stored exclusively in a **SQLite database on your device**. No internet communication takes place.

**With Plus:**
- Google Drive Sync data is stored in your own Google Drive account.  
- Audio and text data sent for AI processing is transmitted over HTTPS and not stored by the Cloudflare proxy.  
- OpenAI does not use data submitted via the API to train its models (per OpenAI's data usage policy as of 2026).

**Your responsibility:**  
Securing your device (e.g., screen lock, device encryption) is your responsibility.

---

## 5. Third‑Party Services

### Without Plus
The app does not use any third‑party services, analytics tools, advertising networks, or tracking technologies. **No data is shared** with any third parties.

### With SouvenirBird Plus

**Google (Sign‑In & Drive)**  
Used for authentication and cloud backup. Your souvenir data is stored in your own Google Drive account.  
Privacy policy: https://policies.google.com/privacy

**OpenAI**  
Audio recordings (Whisper transcription) and text snippets (AI text polish) are forwarded to OpenAI for processing. OpenAI does not use API‑submitted data to train its models by default.  
Privacy policy: https://openai.com/policies/privacy-policy

**Cloudflare Workers**  
A Cloudflare Worker acts as a reverse proxy between the app and OpenAI. The proxy does not store any data; it only forwards requests and responses.  
Privacy policy: https://www.cloudflare.com/privacypolicy/

All Plus features are opt-in. When a Plus feature is disabled, no data is sent to the corresponding service.

---

## 6. Export & Import
You can **export your data** at any time in the following formats:

- CSV export  
- PDF export  
- Database backup (.db file)  

You can also **import** a previously saved database backup.

The app never transfers data automatically. All exports are initiated by you and remain under your control.

---

## 7. Legal Basis (GDPR)
The legal basis for processing your data is **Art. 6(1)(a) GDPR** – consent by actively using the app and entering personal information.

---

## 8. Your Rights
Under the GDPR, you have the following rights:

- **Right of access** (Art. 15 GDPR)  
- **Right to rectification** (Art. 16 GDPR)  
- **Right to erasure** (Art. 17 GDPR)  
- **Right to data portability** (Art. 20 GDPR)  

You can exercise these rights at any time:

- Edit or delete your data directly in the app  
- Export your data using the built‑in export functions  
- Uninstall the app to remove all data from your device  

---

## 9. Hosting of This Privacy Policy (GitHub Pages)
This privacy policy is provided via a website hosted on **GitHub Pages**.

When accessing the website, GitHub may automatically collect technical information such as:

- IP address  
- browser type  
- operating system  
- time of access  

This processing is carried out solely by GitHub in accordance with their privacy statement.

I do not have access to these server logs and do not process this data myself.

GitHub Privacy Statement:  
https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement

---

## 10. Contact
For any privacy‑related inquiries, please contact:  
**hello@lueders.app**

---

_Last updated: 2026_
