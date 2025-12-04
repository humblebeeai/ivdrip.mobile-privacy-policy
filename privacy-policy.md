# Privacy Policy

**Last Updated:** December 4, 2025

## 1. Introduction

Epic Medical ("we," "our," or "us") operates the Drip Counter mobile application (the "App"). This Privacy Policy explains how we collect, use, disclose, and safeguard your information when you use our App. Please read this Privacy Policy carefully. By using the App, you agree to the collection and use of information in accordance with this policy.

## 2. Information We Collect

### 2.1 Account Information
When you create an account or sign in to the App, we collect:
- Email address
- Password (stored securely and encrypted)
- Authentication tokens and session information

### 2.2 Device Information
We automatically collect certain device information, including:
- Device name and model
- Unique device identifier
- Session identifiers
- Operating system and platform information
- Device orientation and performance metrics

### 2.3 Camera and Image Data
The App requires access to your device's camera to monitor IV drip flow rates. We collect:
- Real-time camera feed data (processed in real-time, not stored as video)
- Processed image frames used for drip detection and measurement
- Segmentation masks and analysis data derived from camera images
- Cropped image frames (160x160 pixels) used for machine learning inference

**Note:** Camera data is processed in real-time for measurement purposes. Images may be stored locally on your device or uploaded to cloud storage for analysis and quality improvement purposes.

### 2.4 Measurement and Analysis Data
We collect data related to IV drip monitoring, including:
- Drip detection measurements (nozzle width, height, mask areas)
- Flow rate calculations and predictions
- Timestamp information for each measurement
- Session identifiers linking measurements together
- Inference and frame identification data
- Calculated ratios and normalized measurements

### 2.5 Usage Data
We may collect information about how you use the App, including:
- App performance metrics (frame rate, processing times)
- Feature usage patterns
- Error logs and diagnostic information

### 2.6 Authentication and Security Data
- Passcode validation status (stored securely)
- Email verification status
- Login and session activity

## 3. How We Use Your Information

We use the collected information for the following purposes:

### 3.1 Core Functionality
- To provide and maintain the App's IV drip monitoring services
- To authenticate your identity and secure your account
- To process camera data and generate flow rate measurements
- To deliver real-time analysis and predictions

### 3.2 Service Improvement
- To improve the accuracy of our machine learning models
- To enhance App performance and user experience
- To develop new features and functionality
- To conduct research and analysis (using anonymized data)

### 3.3 Technical Operations
- To maintain and troubleshoot the App
- To ensure security and prevent fraud
- To comply with legal obligations
- To respond to your inquiries and provide support

## 4. Data Storage and Security

### 4.1 Local Storage
Some data is stored locally on your device, including:
- Device identifiers and session information (stored using Unity PlayerPrefs)
- CSV files containing measurement data
- Processed images and frames (if saving is enabled)
- Authentication tokens and user preferences

**Note:** Local data persists until you uninstall the App or manually delete it.

### 4.2 Cloud Storage
We use third-party cloud services to store certain data:
- **Firebase Storage:** Images, measurement data, and metadata are uploaded to Firebase Storage
- **Firebase Firestore:** Passcode validation data and user authentication status
- **WebSocket Servers:** Real-time transmission of measurement data to our servers

### 4.3 Data Security
We implement appropriate technical and organizational measures to protect your information:
- Encrypted data transmission (HTTPS, secure WebSocket connections)
- Secure authentication using Firebase Authentication
- Encrypted password storage
- Access controls and authentication requirements
- Regular security assessments

However, no method of transmission over the internet or electronic storage is 100% secure. While we strive to use commercially acceptable means to protect your information, we cannot guarantee absolute security.

## 5. Third-Party Services

The App uses the following third-party services that may collect, process, or store your information:

### 5.1 Google Firebase Services
- **Firebase Authentication:** Handles user sign-up, sign-in, and account management
- **Firebase Storage:** Stores images and measurement data
- **Firebase Firestore:** Stores passcode validation and user data
- **Firebase Analytics:** Disabled - we do not collect advertising IDs or analytics data

**Firebase Privacy Policy:** https://firebase.google.com/support/privacy

### 5.2 WebSocket Services
- Real-time data transmission to our servers for analysis and storage
- Data is transmitted securely using encrypted WebSocket connections

### 5.3 OpenCV for Unity
- Image processing library used for computer vision operations
- Processes camera data locally on your device

## 6. Data Sharing and Disclosure

We do not sell, trade, or rent your personal information to third parties. We may share your information only in the following circumstances:

### 6.1 Service Providers
We may share information with third-party service providers who perform services on our behalf, such as:
- Cloud storage providers (Firebase/Google Cloud)
- Data processing and analysis services
- Technical support and maintenance services

### 6.2 Legal Requirements
We may disclose your information if required to do so by law or in response to valid requests by public authorities (e.g., a court or government agency).

### 6.3 Business Transfers
In the event of a merger, acquisition, or sale of assets, your information may be transferred as part of that transaction.

### 6.4 With Your Consent
We may share your information with your explicit consent or at your direction.

## 7. Your Rights and Choices

You have the following rights regarding your personal information:

### 7.1 Access and Correction
- You can access and update your account information through the App settings
- You can request a copy of your personal data by contacting us

### 7.2 Data Deletion
- You can delete your account and associated data by contacting us at contact@humblebee.ai
- You can delete locally stored data by uninstalling the App
- Note: Some data may be retained for legal or legitimate business purposes

### 7.3 Camera Access
- You can revoke camera permissions through your device settings
- Note: The App requires camera access to function; revoking this permission will prevent the App from operating

### 7.4 Account Management
- You can sign out of your account at any time
- You can change your password through the App's account settings

## 8. Data Retention

We retain your information for as long as necessary to:
- Provide you with the App's services
- Comply with legal obligations
- Resolve disputes and enforce our agreements
- Improve our services and develop new features

Measurement data and images may be retained for research and model improvement purposes, but will be anonymized where possible. You can request deletion of your data at any time by contacting us.

## 9. Children's Privacy

The App is not intended for use by children under the age of 13 (or the applicable age of consent in your jurisdiction). We do not knowingly collect personal information from children. If you are a parent or guardian and believe your child has provided us with personal information, please contact us immediately. If we become aware that we have collected personal information from a child without verification of parental consent, we will take steps to delete that information.

## 10. International Data Transfers

Your information may be transferred to and processed in countries other than your country of residence. These countries may have data protection laws that differ from those in your country. By using the App, you consent to the transfer of your information to these countries, including:
- United States (where Firebase/Google Cloud services are hosted)
- Other countries where our service providers operate

We ensure that appropriate safeguards are in place to protect your information in accordance with this Privacy Policy.

## 11. Health Information

The App processes data related to IV drip monitoring, which may be considered health-related information in some jurisdictions. We treat this information with additional care and in accordance with applicable health information privacy laws. However, this App is intended for monitoring and measurement purposes only and is not a medical device. The data collected should not be used as a substitute for professional medical advice, diagnosis, or treatment.

## 12. Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by:
- Posting the new Privacy Policy in the App
- Updating the "Last Updated" date at the top of this Privacy Policy
- Providing in-app notifications for material changes

You are advised to review this Privacy Policy periodically for any changes. Changes to this Privacy Policy are effective when they are posted.

## 13. Your Consent

By using the App, you consent to:
- The collection and use of information as described in this Privacy Policy
- The processing of camera data for IV drip monitoring
- The transmission of data to third-party services (Firebase, WebSocket servers)
- The storage of data locally on your device and in cloud services

## 14. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact us:

**Epic Medical**  
Email: contact@humblebee.ai

We will respond to your inquiries within a reasonable timeframe.

## 15. Additional Information for Specific Regions

### 15.1 European Economic Area (EEA) and United Kingdom
If you are located in the EEA or UK, you have additional rights under the General Data Protection Regulation (GDPR), including:
- Right to access your personal data
- Right to rectification of inaccurate data
- Right to erasure ("right to be forgotten")
- Right to restrict processing
- Right to data portability
- Right to object to processing
- Right to withdraw consent

To exercise these rights, please contact us at contact@humblebee.ai.

### 15.2 California Residents
If you are a California resident, you have additional rights under the California Consumer Privacy Act (CCPA), including:
- Right to know what personal information is collected
- Right to delete personal information
- Right to opt-out of the sale of personal information (we do not sell personal information)
- Right to non-discrimination for exercising your privacy rights

To exercise these rights, please contact us at contact@humblebee.ai.

## 16. Medical Disclaimer

**IMPORTANT:** The Drip Counter App is designed for monitoring and measurement purposes only. It is not a medical device and should not be used as a substitute for professional medical advice, diagnosis, or treatment. Always seek the advice of qualified health providers with any questions you may have regarding a medical condition. Never disregard professional medical advice or delay in seeking it because of information provided by this App.
