# Privacy Policy for MediMate
 
**Last updated:** September 2026
 
This Privacy Policy describes how MediMate ("the App," "we," "us," or "our") collects, uses, and discloses information when you use our mobile application. MediMate is a medicine organization and reminder application for individuals and families.
 
If you have any questions about this Privacy Policy, you can contact us at **softcodes18@gmail.com**.
 
---
 
## 1. Overview
 
MediMate helps you organize medicine schedules, set reminders, track adherence, and manage medicines for family members. We built MediMate with privacy as a core principle: your data is stored in your own private account and is never sold, shared with advertisers, or used to profile you.
 
MediMate is **not** a medical device and does not provide medical advice, diagnosis, or treatment recommendations. See the "Medical Disclaimer" section of the app for more details.
 
---
 
## 2. Information We Collect
 
### 2.1 Account Information
When you create an account, we collect:
- Your name
- Your email address
- Authentication credentials (managed securely by Firebase Authentication; we never see or store your raw password)
If you sign in with Google, we receive your name, email address, and profile photo (if available) from Google, consistent with the permissions you grant during sign-in.
 
### 2.2 Family Member Profiles
You may create profiles for family members whose medicines you manage. This may include:
- Name
- Relationship to you (e.g., parent, spouse, child)
- Optional age range
- Optional avatar image
We do not require or request government-issued identification, precise date of birth, or other sensitive identifiers for family member profiles.
 
### 2.3 Medicine and Health-Related Information
To provide the app's core functionality, we store information you enter about medicines, including:
- Medicine name, strength, and dose (exactly as you enter it)
- Frequency and reminder schedule times
- Start and end dates
- Food instructions (e.g., before/after food)
- Notes you add
- Stock quantity and refill thresholds
- A log of whether a scheduled dose was marked as taken, skipped, or missed
**This information is sensitive personal health information**, and we treat it accordingly. It is stored in your private Firestore database record and is never shared with other users or third parties for advertising or marketing purposes.
 
### 2.4 Prescription Photos
If you use the "Scan Prescription" feature, you may take or select a photo of a prescription. This photo is processed on your device (or transmitted briefly for processing) solely to extract text so you can review and confirm the details yourself. **Prescription images are not stored permanently.** Temporary files created during scanning are deleted immediately after processing. Any information extracted from a scanned prescription is always shown to you for review and manual confirmation before it is saved — we never save prescription-derived data automatically.
 
### 2.5 Usage and Analytics Data
We use Firebase Analytics to understand basic product usage, limited to structural events such as:
- App opened
- Onboarding completed
- A medicine was created, marked taken, or skipped
- The prescription scanner was started or completed
- The subscription screen was viewed
- A subscription was started
**We do not send medicine names, dosage details, notes, prescription text, or any other sensitive health content to our analytics provider.**
 
### 2.6 Crash and Diagnostic Data
We use Firebase Crashlytics to detect and fix technical problems (app crashes and errors). Crash reports may include device information (device model, OS version, app version) and a technical stack trace. We do not intentionally include personal health data in crash logs.
 
### 2.7 Subscription and Payment Information
If you purchase MediMate Pro, the transaction is processed entirely by Google Play Billing. **We do not receive or store your payment card, UPI, or other financial account details.** We only receive confirmation of your subscription status (active/expired) to unlock Pro features on your account.
 
### 2.8 Notification Preferences
We store your notification and reminder preferences (e.g., whether voice reminders are enabled) to personalize your experience. Local reminder notifications are scheduled and delivered on your device and do not require sending your medicine data to us at the time of the reminder.
 
---
 
## 3. How We Use Your Information
 
We use the information described above to:
- Create and manage your account
- Provide medicine reminders and scheduling
- Allow you to organize medicines for multiple family members
- Track medicine-taking history and simple adherence statistics (e.g., "taken 90% of scheduled reminders")
- Send low-stock and refill notifications you have configured
- Maintain and improve the app's reliability and performance
- Provide customer support
- Process subscription purchases through Google Play Billing
- Comply with legal obligations
We do **not** use your data to:
- Diagnose any medical condition
- Recommend, change, or suggest medication or dosage
- Make any claims about the effectiveness of your treatment
- Sell or rent your information to third parties
- Serve targeted third-party advertising based on your health data
---
 
## 4. Third-Party Services
 
MediMate uses the following third-party services to operate. Each provider processes data under its own privacy policy and applicable data protection agreements:
 
| Service | Purpose | Data Involved |
|---|---|---|
| Firebase Authentication (Google) | Account creation and sign-in | Email, name, authentication tokens |
| Cloud Firestore (Google) | Secure storage of your account, family members, medicines, and history | All app data described above |
| Firebase Cloud Messaging (Google) | Push notifications (where applicable) | Device token |
| Firebase Analytics (Google) | Product usage analytics | Limited, non-health event data (see 2.5) |
| Firebase Crashlytics (Google) | Crash and error reporting | Device/technical diagnostic data |
| Google Sign-In | Optional authentication method | Name, email, profile photo |
| Google Play Billing | Subscription purchases | Purchase/subscription status only |
 
You can review Google's privacy practices at: https://policies.google.com/privacy
 
---
 
## 5. Data Storage and Security
 
Your data is stored in Cloud Firestore, secured by security rules that ensure **only you can read or write your own account data** — no other user of MediMate can access your family members, medicines, or history. We use industry-standard practices, including encrypted connections (HTTPS/TLS), to protect data in transit.
 
While we take reasonable steps to protect your information, no method of electronic storage or transmission is 100% secure, and we cannot guarantee absolute security.
 
---
 
## 6. Data Retention and Deletion
 
You may delete your account at any time from **Profile → Delete Account** within the app. Deleting your account permanently removes your profile, family member records, medicines, reminders, and history from our systems. This action cannot be undone.
 
Prescription photos are not retained beyond the immediate processing needed to extract text for your review, as described in Section 2.4.
 
If you would like to request deletion of your data without using the in-app option, you may contact us at **softcodes18@gmail.com**.
 
---
 
## 7. Children's Privacy
 
MediMate is intended for use by adults managing medicine schedules for themselves and their family members. The app is not directed at children, and we do not knowingly collect account registration information directly from children under 13 (or the relevant minimum age in your jurisdiction). Family member profiles for a child may be created and managed by a parent or guardian using their own account.
 
If you believe a child has provided us with personal information through their own account, please contact us at **softcodes18@gmail.com** so we can take appropriate action.
 
---
 
## 8. Your Rights and Choices
 
Depending on your location, you may have rights to:
- Access the personal data we hold about you
- Correct inaccurate data
- Request deletion of your data
- Object to or restrict certain processing
- Request a copy of your data in a portable format
You can exercise most of these rights directly within the app (editing or deleting family members, medicines, or your account). For any other requests, contact us at **softcodes18@gmail.com**.
 
---
 
## 9. International Data Transfers
 
Our third-party service providers (Google/Firebase) may process and store data in data centers located in various countries. By using MediMate, you acknowledge that your information may be transferred to and processed in countries other than your country of residence, which may have different data protection laws.
 
---
 
## 10. Changes to This Privacy Policy
 
We may update this Privacy Policy from time to time to reflect changes in our practices or for legal, operational, or regulatory reasons. We will update the "Last updated" date at the top of this policy when changes are made. Continued use of the app after changes take effect constitutes acceptance of the revised policy.
 
---
 
## 11. Medical Disclaimer
 
MediMate is a medicine organization and reminder tool. It does not provide medical diagnosis, treatment recommendations, or professional medical advice. Always follow the instructions provided by your qualified healthcare professional and verify prescription information before use.
 
---
 
## 12. Contact Us
 
If you have any questions, concerns, or requests regarding this Privacy Policy or your data, please contact us at:
 
**Email:** softcodes18@gmail.com
