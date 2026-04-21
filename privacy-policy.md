# Privacy Policy — FastUGC

**Last updated:** April 21, 2026

FastUGC ("we", "us") is an iOS application that generates AI-powered user-generated-content (UGC) style videos — including AI avatars and AI voice-overs — for marketing, product promotion, and social content. This Privacy Policy explains what data we collect, why we collect it, and how we protect it.

## 1. Data we collect

### 1.1 Account data
When you sign in with Apple or Google, we receive your **email address** and, if provided by the identity provider, your **display name**. If you sign in anonymously, we assign you a random user ID and collect no personal data.

### 1.2 Onboarding & profile data
During onboarding you may tell us about your **business/brand**, **target audience**, **content goals**, and **preferred video style**. This data is stored in your own user document and is used exclusively to personalize the videos we generate for you.

### 1.3 User-generated content
- **Scripts**, **product descriptions**, **hooks**, and **captions** you create or paste in the app.
- **Generated videos** (AI avatar + voice-over output) produced from your inputs.
- **Generated audio** files produced via our text-to-speech provider.
- **Avatar and voice selections** you make from the in-app library.
- **Generation history** — which videos you created, their length, and usage.

### 1.4 Subscription data
If you purchase a subscription, we receive **purchase state** (active/expired, plan, expiry date) from Apple via RevenueCat. We do not receive your credit card number or billing address.

### 1.5 Device & diagnostic data
- Device type and iOS version (for crash reports and aggregate analytics only).
- Anonymous app usage events (screens viewed, features used) — used only to improve the app.

### 1.6 What we do NOT collect
- We do not collect your **precise location**.
- We do not access your **contacts**, **photos**, **microphone**, or **health data** unless you explicitly grant permission to import media into the app.
- We do not use **advertising identifiers** (IDFA) or perform cross-app tracking.
- We do not sell your data to any third party.

## 2. How we use your data

| Purpose | Data used |
|---|---|
| Personalizing generated videos | Brand, audience, goals, style preferences |
| Generating voice-overs and videos | Text/scripts you provide (sent to generation providers) |
| Keeping your library in sync across devices | User ID, project documents, video URLs |
| Managing your subscription | Purchase state, user ID |
| Improving the app | Aggregate usage events, crash reports |

## 3. Third-party services

FastUGC uses the following processors. Each has its own privacy practices — please review theirs as well:

- **Apple** (Sign in with Apple, StoreKit, App Store purchases) — https://www.apple.com/legal/privacy/
- **Google / Firebase** (authentication, Firestore database, cloud storage) — https://firebase.google.com/support/privacy
- **RevenueCat** (subscription management) — https://www.revenuecat.com/privacy
- **ElevenLabs** (text-to-speech voice generation) — https://elevenlabs.io/privacy. We send the script text you provide; we do not send personal identifiers.

## 4. Where your data is stored

Data is stored in **Google Cloud Platform** (Firebase) in regions determined by Firebase's multi-region replication. Generated videos and audio are stored in **Firebase Storage**. Subscription state is held by **Apple** and **RevenueCat** (United States).

## 5. Data retention

- **Active account:** your data is retained as long as your account is active.
- **Account deletion:** from the app's Profile → Delete Account, you can permanently delete your account. We delete your user doc and all subcollections (projects, scripts, generated videos, audio) and associated media files within **30 days**. Backup copies are purged within **90 days**.
- **Subscription receipts:** Apple retains purchase receipts per its own policies.

## 6. Your rights

Depending on your location, you may have the right to:
- **Access** the data we hold about you.
- **Correct** inaccurate data.
- **Delete** your data (see Account Deletion above).
- **Port** your data to another service.
- **Object** to processing or **restrict** it.
- **Withdraw consent** where processing is based on consent.

To exercise any of these rights, contact us at **support@fastugc.app**.

## 7. Children's privacy

FastUGC is intended for users **aged 13 and older** (or the minimum age in your country, whichever is higher). We do not knowingly collect data from children under this age. If you believe a child has provided us with data, contact us and we will delete it.

## 8. Security

All data in transit is encrypted via TLS. Data at rest in Firebase and Firebase Storage is encrypted at the infrastructure layer. We apply the principle of least privilege — only our backend services and the signed-in user can read their own data.

## 9. Changes to this policy

If we materially change this policy, we will update the "Last updated" date at the top and, for significant changes, notify you in-app. Continued use of the app after changes means you accept the updated policy.

## 10. Contact

Questions about this policy or your data?

**Email:** support@fastugc.app
**Developer:** Isa Mercan
**Country:** Turkey
