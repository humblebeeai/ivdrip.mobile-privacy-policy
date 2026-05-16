# Privacy Policy

**Last Updated:** May 16, 2026

## 1. Introduction

EPIC MEDICAL PTE. LTD. ("we," "our," or "us") operates the RxDrop mobile application (the "App"). This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use our App. Please read this Privacy Policy carefully. By using the App, you agree to the collection and use of information in accordance with this policy.

RxDrop is designed to minimize the data we collect and store. We only collect the information described below.

## 2. Information We Collect

### 2.1 Account Information
When you create an account or sign in to the App, we collect:
- Email address
- Password (stored securely as a hash by our authentication provider; never stored or transmitted in plain text)
- Authentication tokens and session information

### 2.2 Saved Flow Rate Results
The App calculates IV drip flow rates from your device's camera in real time. By default, these measurements are **not** stored. If you tap the **Save** button for a particular measurement, the resulting flow rate value (and an associated timestamp) is saved to your account.

Measurements that you do not explicitly save are discarded as soon as the next measurement begins.

### 2.3 Authentication Diagnostics
Our authentication provider (Firebase Authentication) records limited information necessary to operate the sign-in service, such as the time of your sign-in and the IP address from which the request originated. We do not use this information for any other purpose.

## 3. How We Use Your Information

We use the limited information we collect for the following purposes only:

### 3.1 Core Functionality
- To authenticate your identity and secure your account
- To save and retrieve flow rate results that you explicitly chose to save

### 3.2 Technical Operations
- To maintain and troubleshoot the App
- To ensure security and prevent fraudulent account use
- To comply with legal obligations
- To respond to your inquiries and provide support

## 4. Data Storage and Security

### 4.1 Local Storage
The following data is stored locally on your device:
- Authentication tokens and user preferences
- Flow rate results that you chose to save (cached for offline access)

Local data persists until you uninstall the App or delete it through your device settings.

### 4.2 Cloud Storage
We use Google Firebase to store account information and saved flow rate results:
- **Firebase Authentication** stores your email address and the hash of your password.
- **Firebase Firestore** stores the flow rate results you have explicitly saved, associated with your account.

### 4.3 Data Security
We implement appropriate technical and organizational measures to protect your information:
- Encrypted data transmission (HTTPS)
- Secure authentication using Firebase Authentication
- Password hashing handled by Firebase Authentication
- Access controls on our cloud resources

## 5. Third-Party Services

The App uses the following third-party services:

### 5.1 Google Firebase
- **Firebase Authentication:** Handles user sign-up, sign-in, and account management. Stores email and password hash.
- **Firebase Firestore:** Stores flow rate results that you explicitly saved.

**Firebase Privacy Policy:** https://firebase.google.com/support/privacy

## 6. Data Sharing and Disclosure

We do not sell, trade, or rent your personal information to third parties. We may share your information only in the following circumstances:

### 6.1 Service Providers
We share account information and saved flow rate results with Google Firebase, our cloud infrastructure provider, solely for the purpose of operating the App.

### 6.2 Legal Requirements
We may disclose your information if required to do so by law or in response to valid requests by public authorities (e.g., a court or government agency).

### 6.3 Business Transfers
In the event of a merger, acquisition, or sale of assets, your information may be transferred as part of that transaction.

### 6.4 With Your Consent
We may share your information with your explicit consent or at your direction.

## 7. Your Rights and Choices

### 7.1 Access and Correction
- You can view and update your account information through the App settings.
- You can request a copy of your personal data by contacting us.

### 7.2 Account and Data Deletion
- You can request deletion of your account and associated data at any time by using the [account deletion request form](./data-safety.md) or by emailing **vision@humblebee.ai**.
- You can delete locally stored data by uninstalling the App.

### 7.3 Camera Access
- The App requires camera access to calculate flow rates.
- You can revoke camera permissions through your device settings. Note that the App cannot perform measurements without camera access.

### 7.4 Account Management
- You can sign out of your account at any time.
- You can change your password through the App's account settings.

## 8. Data Retention

We retain your account information and saved flow rate results for as long as your account is active. When you request account deletion, all account information and saved flow rate results are deleted within 30 days. Residual copies may persist in our cloud provider's encrypted backup systems for a short additional period (typically up to 30 days) before being overwritten in the normal course of backup rotation.

See our [Account Deletion Request page](./data-safety.md) for details.

## 9. International Data Transfers

Your information may be transferred to and processed in countries other than your country of residence. These countries may have data protection laws that differ from those in your country. By using the App, you consent to the transfer of your information to these countries, including the United States (where Firebase/Google Cloud services are hosted).

We ensure that appropriate safeguards are in place to protect your information in accordance with this Privacy Policy.

## 10. Medical Information

The App calculates IV drip flow rates and may save those results at your request. We do not collect patient identifiers or records, and the App is intended for monitoring and measurement purposes only. RxDrop is not a medical device and the data it produces should not be used as a substitute for professional medical advice, diagnosis, or treatment.

## 11. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by:
- Posting the new Privacy Policy in the App
- Updating the "Last Updated" date at the top of this Privacy Policy
- Providing in-app notifications for material changes

You are advised to review this Privacy Policy periodically for any changes. Changes to this Privacy Policy are effective when they are posted.

## 12. Your Consent

By using the App, you consent to:
- The collection and use of information as described in this Privacy Policy
- The on-device processing of camera data for IV drip flow rate measurement
- The storage of your account information and any flow rate results you choose to save

## 13. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact us:

Email: vision@humblebee.ai

We will respond to your inquiries within a reasonable timeframe.