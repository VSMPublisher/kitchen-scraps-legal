# Privacy Policy

**Effective Date:** September 6, 2026  
**Last Updated:** September 6, 2026

[TOC]

## 1. Introduction

Virender Singh ("we," "our," or "us") operates the **Kitchen Scraps & Food Waste Quiz App** (the "App"). We are committed to protecting your privacy. This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use our App on Android, Windows Desktop, or the Web.

Please read this Privacy Policy carefully. By using the App, you agree to the collection and use of information in accordance with this policy.

## 2. Information We Collect

### A. Information We Do NOT Collect

We believe in strict data minimality. We do **not** collect, store, or transmit:

- Your real name, phone number, or physical address
- Email addresses (except when you voluntarily submit feedback or contact us)
- Photographs, contacts, or other media from your device
- Precise geolocation data

### B. Automatically Collected Information

When you use the App, certain information may be automatically collected:

- **Device Information:** Device model, operating system version, and unique device identifiers (used for analytics and ad delivery).
- **Usage Data:** Quiz scores, streak progress, hints used, time spent per question, and general interaction patterns. This data is anonymous and used to improve quiz difficulty and content quality.
- **Advertising Identifiers:** Google Advertising ID (AAID) on Android devices, used for ad personalization.

### C. Data Stored Locally on Your Device

The following data is stored entirely on your device using local storage (SharedPreferences) and is **never transmitted to our servers** unless you explicitly enable cloud sync:

- Quiz progress, high scores, and category statistics
- Virtual credits balance and streak history
- Bookmarked questions and personal notes
- Custom quiz questions you create
- Saved compost audit reports
- Theme preferences (dark mode, Amber Gold skin)
- Sound, haptic, and language settings
- Daily challenge streaks
- Onboarding completion status

### D. Cloud-Synced Data (Optional)

If cloud sync is active, the following data may be stored in **Google Firestore** under a anonymized device identifier:

- Quiz progress and high scores
- Virtual credits balance
- Category performance statistics

This data is linked only to a randomly generated device UUID—not to your personal identity. You can disconnect cloud sync or reset all progress at any time from the Settings screen.

## 3. How We Use Your Information

We use the information we collect to:

- Operate, maintain, and improve the App's functionality and educational content
- Track and manage your virtual credits, streaks, and achievement progress
- Analyze quiz performance to optimize question difficulty and identify popular content (via anonymous analytics)
- Serve personalized or non-personalized advertisements through Google AdMob to support the free operation of the App
- Deliver rewarded video ads (for hints and streak saves) on Android devices
- Process and respond to your feedback and support requests
- Verify creator identities for the Creator Suite feature (email verification only)

## 4. Third-Party Services

We integrate the following third-party services that may collect information:

### A. Google AdMob (Android Only)

We use Google AdMob to serve rewarded video ads. AdMob may collect:

- Device ID and advertising identifier
- Approximate location (based on IP address)
- App usage data for ad personalization

You can opt out of personalized advertising in your Android device settings. Ads are only shown on Android; web and desktop users receive auto-granted rewards with no ads displayed.

**Google Ads Privacy:** [https://policies.google.com/technologies/partner-sites](https://policies.google.com/technologies/partner-sites)

### B. Google Firebase

We use Firebase services for:

- **Cloud Firestore:** Optional cloud storage for user progress sync, creator quiz submissions, and feedback storage
- **Firebase Analytics:** Anonymous event tracking (quiz completions, screen views, feedback submissions) to improve content quality
- **Firebase Remote Config:** Remote configuration for app settings such as quiz time limits, hint costs, and maintenance mode

### C. Google User Messaging Platform (UMP)

On Android, we use Google's UMP SDK to request GDPR consent for personalized advertising before initializing AdMob.

### D. Google Apps Script

Used as a backend service for:

- Sending and verifying email OTPs for creator identity verification
- Processing creator quiz submissions

### E. MyMemory Translation API

Used to automatically translate user-generated quiz content into the app's supported languages.

### F. Text-to-Speech Services

- **Android/iOS:** Native `flutter_tts` for reading questions aloud
- **Web:** Web Speech API for browser-based text-to-speech

## 5. Creator Suite & User-Generated Content

The App includes a **Creator Suite** feature that allows content creators to submit custom quiz questions. This feature involves:

- **Email Verification:** Your email address is collected solely for identity verification via a one-time password (OTP). Your email is stored locally on your device and is not shared with third parties.
- **Social Media Verification:** Creators may verify ownership of YouTube channels or social media accounts by completing verification steps (e.g., posting a comment). This is used only to confirm creator identity.
- **Quiz Submissions:** Creator-submitted quiz content is stored in Firebase Firestore and made available to other users through the Creator Directory.
- **Follower Count Verification:** We check publicly available follower counts to verify creator eligibility. We do not store or track your social media accounts beyond this verification step.

## 6. User-Generated Content & Sharing

- **Custom Quiz Builder:** You can create your own quiz questions from JSON files. This data is stored locally on your device only.
- **Bookmarks & Notes:** Questions you bookmark and any notes you add are stored locally on your device only.
- **Compost Audit Reports:** Generated audit reports are stored locally and can be shared via your device's native share sheet.
- **Social Share Cards:** When you choose to share quiz results or achievements, the App generates a shareable image card. Sharing is entirely voluntary and uses your device's native sharing capabilities.

## 7. Advertising & Rewards

- On Android, you can watch **rewarded video ads** to earn free hints or save your streak. Rewards are granted by Google AdMob's server-side verification.
- On web and desktop platforms, rewards are auto-granted without requiring you to watch ads.
- We do not control the content of third-party advertisements displayed through AdMob.

## 8. Children's Privacy

The App is designed as an educational eco-education tool suitable for all age groups. We adhere to child-safety regulations (COPPA) and do not knowingly collect personal data from children under the age of 13. If you are a parent or guardian and believe your child has provided us with personal data, please contact us immediately so we can delete it.

## 9. Data Protection Rights

### A. GDPR Rights (European Economic Area)

If you are a resident of the EEA, you have the right to:

- **Access** your personal data
- **Rectify** inaccurate personal data
- **Erase** your personal data
- **Object** to processing of your personal data
- **Data portability** — request a copy of your data in a structured format

### B. CCPA Rights (California)

If you are a California resident, you have the right to:

- **Know** what personal information is collected about you
- **Delete** your personal information
- **Opt out** of the sale of personal information (advertising identifiers used for ad personalization may constitute a "sale" under CCPA)
- **Non-discrimination** — we will not discriminate against you for exercising your rights

To exercise any of these rights, contact us at kitchenscrapsquiz@gmail.com.

## 10. Data Security

We implement industry-standard security measures including:

- HTTPS-only communication (cleartext traffic disabled)
- Firebase security rules for Firestore access control
- Local encryption of sensitive data where supported by the device

However, no method of electronic transmission or storage is 100% secure, and we cannot guarantee absolute security.

## 11. Data Retention

- **Local data:** Retained on your device until you choose to reset progress or uninstall the App.
- **Cloud data:** Retained in Firebase Firestore until you request deletion or reset your progress.
- **Feedback submissions:** Retained in Firestore for customer support purposes.
- **Creator submissions:** Retained in the Creator Directory until a creator requests removal.

## 12. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. If we make material changes, we will update the "Last Updated" date at the top of this page. Continued use of the App after changes constitutes acceptance of the revised policy.

## 13. Contact Us

If you have questions about this Privacy Policy or wish to exercise your data protection rights, please contact us:

- **Name:** Virender Singh
- **Email:** kitchenscrapsquiz@gmail.com
- **Address:** Delhi, India
