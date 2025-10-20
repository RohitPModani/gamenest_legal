---
layout: page
title: Privacy Policy
---

**Effective Date:** October 11, 2025  
**Last Updated:** October 20, 2025

---

## Introduction

Welcome to Listist ("we," "us," "our," or "the App"). We are committed to protecting your privacy and ensuring transparency about how we collect, use, and safeguard your personal information.

This Privacy Policy explains our practices regarding data collection, usage, storage, and your rights when you use the Listist mobile application and related services (collectively, "the Service"). By using Listist, you agree to the collection and use of information in accordance with this policy.

If you do not agree with any part of this Privacy Policy, please discontinue use of the Service immediately.

---

## 1. Information We Collect

We collect several types of information to provide and improve our Service.

### 1.1 Information You Provide Directly

#### Account Information
- **Google Sign-In:** When you authenticate using Google Sign-In, we receive your Google account ID, email address, display name, and profile photo. This information is provided by Google and is used to create and manage your account.
- **Anonymous Usage:** If you choose to use the App without signing in, we generate and store a random anonymous identifier locally on your device. This identifier allows you to maintain your data between sessions.

#### Content You Create
- **Lists:** Titles, categories, notes, creation timestamps, and modification history.
- **List Items:** Titles, notes, URLs, completion status, and associated metadata.
- **Groups:** Names, descriptions, colors, icons, and list assignments.
- **Collaboration Data:** 
  - Invitations you send (recipient email addresses, invitation status, timestamps)
  - Member roles and permissions
  - Activity logs related to shared lists
- **Friends:** Email addresses and optional display names of contacts you save for quick collaboration.
- **Feedback:** Content, type (bug report, feature request, general), timestamps, and upvotes you submit through the in-app feedback system.

#### Settings and Preferences
- **App Settings:** Theme preference (light/dark/system), language selection, notification preferences, and tutorial/tip status.
- **Notification Settings:** Whether you've enabled or disabled push notifications and specific notification types.

### 1.2 Information Collected Automatically

#### Usage Analytics
- **Firebase Analytics:** Collects anonymized, aggregated data about how you use the App, including:
  - Features you access and how often
  - Screen views and navigation patterns
  - Session duration and frequency
  - Device type, operating system version, and app version
  - General geographic location (country/region level)
  - Language and locale settings
- **Note:** Analytics can be disabled in debug/development builds. In production, data is aggregated and anonymized.

#### Crash and Diagnostic Data
- **Firebase Crashlytics:** Automatically collects information when the App crashes or encounters errors:
  - Stack traces and error logs
  - Device state at time of crash (memory usage, battery level, network status)
  - Device model, operating system version, and app version
  - Anonymized installation identifiers
  - Sequence of actions leading to the crash
- **Purpose:** This data helps us identify and fix bugs, improve stability, and enhance the user experience.

#### Push Notification Tokens
- **Firebase Cloud Messaging (FCM):** When you enable push notifications, Firebase generates a unique device token:
  - Token is tied to your device and app installation
  - Stored in our Supabase database associated with your user account
  - Used exclusively to send you collaboration invitations and app notifications
  - Can be deleted by disabling notifications or uninstalling the App
  - Tokens are automatically refreshed by Firebase when necessary

#### Real-Time Sync Data
- **Supabase Realtime:** When you use the App, we log:
  - Connection events and timestamps
  - Subscription channels you're listening to
  - Real-time sync success/failure events
  - Performance metrics for optimization purposes

#### Network and Performance Data
- **Connectivity Status:** The App monitors your network connection to provide offline functionality and appropriate error messages.
- **API Response Times:** We log response times and error rates to monitor service health and improve performance.
- **Supabase Logs:** Our backend provider (Supabase) may log:
  - IP addresses for security and fraud detection
  - Request timestamps and types
  - Authentication events
  - Query performance metrics

### 1.3 AI Feature Data Collection

When you use our AI-powered features (optional), we collect and process additional data:

#### AI Input Data
- **List Optimization:** When you request AI suggestions for improving a list, we send:
  - List title and category
  - Existing list items (titles, notes, completion status)
  - User preferences and context
- **Item Suggestions:** When you request AI item recommendations, we send:
  - List category and title
  - Existing items in the list
  - Context about the list purpose
- **Natural Language Parsing:** When you use bulk text input with AI parsing, we send:
  - The raw text you enter
  - List context and category
- **Title/Category Extraction:** When you use AI to parse list metadata, we send:
  - Input text describing the list
  - Context for accurate extraction

#### AI Provider
- **Google Generative AI (Gemini):** All AI features are powered by Google's Gemini models (1.5 Flash and Pro).
- **Data Transmission:** Your prompts and context are sent to Google's servers for processing.
- **Google's Policies:** Your data is also subject to Google's Privacy Policy and Terms of Service.
- **Note:** AI features are entirely optional. If you do not use them, no data is sent to Google AI.

#### AI Response Caching
- **Local Caching:** AI responses may be cached locally on your device for faster access.
- **Database Caching:** With your permission, AI responses and semantic embeddings are stored in Supabase:
  - **Purpose:** Reduce API calls, improve response speed, and save costs.
  - **Content:** Cached prompts (text of your requests), responses (AI-generated suggestions), and embeddings (numerical representations of your prompts).
  - **Association:** Cached data is associated with your user ID if you're signed in, or your anonymous ID if using guest mode.
  - **Retention:** Cache is periodically cleaned to remove old or unused entries.
- **Semantic Embeddings:** We generate numerical vector representations of your AI prompts to identify similar requests. These embeddings do not contain readable text but allow us to match semantically similar queries.

---

## 2. How We Use Your Information

We use the collected information for the following purposes:

### 2.1 Core Functionality
- **Provide the Service:** Enable list creation, editing, deletion, real-time synchronization across devices, and collaboration features.
- **Authentication:** Verify your identity, manage your account, and differentiate between anonymous and authenticated users.
- **Data Migration:** Transfer your data from anonymous/guest mode to your authenticated account when you sign in.
- **Collaboration:** Send invitations, manage list members, facilitate real-time collaboration, and notify you of collaboration events.

### 2.2 AI-Powered Features
- **Smart Suggestions:** Provide AI-powered list optimization, item suggestions, category detection, and natural language parsing.
- **Caching:** Store AI responses and embeddings to improve performance, reduce API costs, and provide faster suggestions.
- **Model Training:** Note that Google may use prompts sent to Gemini to improve their AI models, subject to Google's policies.

### 2.3 Communication
- **Notifications:** Send push notifications for collaboration invitations, list updates, and important account information.
- **Email Invitations:** Send email invitations on your behalf when you invite collaborators to lists.
- **Service Updates:** Notify you of important updates, new features, or changes to the Service (via in-app announcements or push notifications).

### 2.4 Service Improvement
- **Analytics:** Understand how users interact with the App to identify popular features, pain points, and opportunities for improvement.
- **Bug Fixing:** Use crash reports and diagnostic data to identify, reproduce, and fix bugs.
- **Performance Optimization:** Monitor API response times, database query performance, and real-time sync reliability to optimize the Service.
- **Feature Development:** Use aggregated usage data and feedback submissions to prioritize new features and improvements.

### 2.5 Security and Compliance
- **Fraud Prevention:** Detect and prevent abuse, spam, unauthorized access, and fraudulent activity.
- **Rate Limiting:** Enforce rate limits (e.g., 5-minute cooldown for feedback submissions) to prevent spam and abuse.
- **Security Monitoring:** Monitor for suspicious activity, unauthorized access attempts, and potential security threats.
- **Legal Compliance:** Comply with applicable laws, regulations, legal processes, and enforceable governmental requests.
- **Terms Enforcement:** Investigate and enforce our Terms & Conditions, including violations of acceptable use policies.

### 2.6 Support
- **Customer Support:** Respond to your inquiries, feedback, bug reports, and feature requests through the in-app feedback system.
- **Account Assistance:** Help you with account-related issues, data recovery, and technical support.

---

## 3. Legal Basis for Processing (GDPR)

If you are located in the European Economic Area (EEA), United Kingdom, or Switzerland, we process your personal data based on the following legal grounds:

### 3.1 Performance of a Contract
- Processing necessary to provide the Service you've requested, including list management, collaboration, and synchronization.

### 3.2 Legitimate Interests
- Improving the Service, preventing fraud, ensuring security, and providing customer support.
- We balance our legitimate interests against your rights and only process data when our interests do not override your fundamental rights.

### 3.3 Consent
- When you enable optional features like AI suggestions, push notifications, or analytics.
- You can withdraw consent at any time through the App settings or by contacting us.

### 3.4 Legal Obligation
- When required to comply with applicable laws, regulations, or legal processes.

---

## 4. How We Share Your Information

We do NOT sell, rent, or trade your personal information to third parties for marketing purposes. We share data only in the following limited circumstances:

### 4.1 With Collaborators
- **Shared Lists:** When you invite someone to collaborate on a list, they can view:
  - List title, category, notes, and items
  - Your display name and email address (as the list owner or a member)
  - Activity logs related to the shared list
- **Control:** You control who you invite. You can remove collaborators at any time.

### 4.2 Service Providers
We use trusted third-party service providers to support our Service:

#### Supabase (Backend Infrastructure)
- **Services:** Database, authentication, real-time synchronization, file storage, and server-side functions.
- **Data Stored:** All user-generated content (lists, items, groups, invitations, friends, feedback), account information, and settings.
- **Data Processing Agreement:** Supabase processes data on our behalf under contractual agreements compliant with GDPR and other data protection laws.
- **Location:** Supabase uses infrastructure hosted by AWS, primarily in regions you may select or default to.
- **Privacy Policy:** [https://supabase.com/privacy](https://supabase.com/privacy)

#### Google (Authentication, Analytics, Notifications, AI)
- **Google Sign-In:** OAuth 2.0 authentication; Google provides account information with your consent.
- **Firebase Analytics:** Anonymized, aggregated usage analytics.
- **Firebase Crashlytics:** Crash reports and diagnostic data for bug fixing.
- **Firebase Cloud Messaging (FCM):** Push notification delivery to your device.
- **Google Generative AI (Gemini):** AI-powered features (list optimization, item suggestions, natural language parsing).
- **Data Processing:** Google processes data under their privacy policies and terms.
- **Privacy Policy:** [https://policies.google.com/privacy](https://policies.google.com/privacy)
- **Note:** Google may use AI prompts to improve their models, subject to their policies.

### 4.3 Aggregated Analytics
- We may share aggregated, anonymized statistics about app usage with partners, investors, or the public (e.g., "10,000 lists created this month").
- This data cannot be used to identify individual users.

### 4.4 Legal and Safety Requirements
We may disclose your information if required to:
- **Comply with Law:** Respond to subpoenas, court orders, legal processes, or enforceable governmental requests.
- **Enforce Terms:** Investigate and enforce violations of our Terms & Conditions.
- **Protect Rights:** Protect the rights, property, or safety of Listist, our users, or the public.
- **Prevent Harm:** Detect, prevent, or address fraud, security issues, or illegal activity.

### 4.5 Business Transfers
If we are involved in a merger, acquisition, asset sale, bankruptcy, or similar transaction, your information may be transferred as part of that transaction. We will notify you via email and/or prominent notice in the App if your data is subject to a different privacy policy.

---

## 5. Data Retention

We retain your information only as long as necessary to fulfill the purposes described in this Privacy Policy:

### 5.1 Active Accounts
- **User-Generated Content:** Lists, items, groups, invitations, friends, and feedback are retained while your account is active.
- **Settings:** Your preferences (theme, language, notifications) are retained while your account is active.

### 5.2 Deleted Accounts
- **Manual Deletion:** You can delete your account and all associated data through the Settings screen in the App.
- **Data Removal:** Upon account deletion, we remove or anonymize your personal data within 30 days, subject to:
  - **Backups:** Residual data may remain in backups for up to 90 days.
  - **Legal Requirements:** We may retain certain data if required by law (e.g., tax records, legal compliance).
  - **Aggregated Data:** Anonymized, aggregated analytics may be retained indefinitely.

### 5.3 Anonymous/Guest Data
- **Local Storage:** Guest data is stored locally on your device. Deleting the App or clearing storage removes this data.
- **Migration:** When you sign in, guest data is migrated to your account and follows the retention policies for authenticated users.

### 5.4 Crash Reports and Analytics
- **Firebase Retention:** Crash reports and analytics data are retained by Firebase according to their default retention policies (typically 60-90 days for crash logs, longer for aggregated analytics).

### 5.5 AI Cache
- **Cached Responses:** AI responses and embeddings are cached in Supabase and periodically cleaned (typically older than 90 days).
- **Manual Deletion:** You can request deletion of your AI cache data by contacting us.

---

## 6. Data Security

We implement industry-standard technical and organizational measures to protect your information:

### 6.1 Encryption
- **In Transit:** All data transmitted between your device and our servers is encrypted using HTTPS/TLS.
- **At Rest:** Supabase encrypts data at rest using AES-256 encryption.
- **Local Storage:** Sensitive data (like tokens) is stored using Flutter Secure Storage, which encrypts data on your device.

### 6.2 Access Controls
- **Row-Level Security (RLS):** Supabase RLS policies ensure users can only access their own data and data explicitly shared with them.
- **Authentication:** Secure OAuth 2.0 authentication via Google Sign-In.
- **Admin Access:** Admin privileges are granted only to authorized team members via email-based verification.
- **Minimal Permissions:** We follow the principle of least privilege—granting only necessary access.

### 6.3 Security Practices
- **Secure Coding:** We follow secure coding practices, including input validation, parameterized queries, and error handling.
- **Dependency Management:** Regular updates to dependencies to patch security vulnerabilities.
- **Monitoring:** Firebase Crashlytics and Supabase logs help us detect and respond to security incidents.
- **No Hardcoded Secrets:** All sensitive credentials are stored as environment variables, not in the codebase.

### 6.4 Limitations
- **No Absolute Security:** While we strive to protect your data, no system is 100% secure. You acknowledge the inherent risks of transmitting data over the internet.
- **Your Responsibility:** Please use a strong Google account password, enable two-factor authentication, and keep your device secure.
- **Report Issues:** If you discover a security vulnerability, please report it to us immediately at support@listist.app.

---

## 7. International Data Transfers

Our service providers (Supabase, Google) operate globally, and your data may be transferred to and processed in countries outside your country of residence, including:
- **United States:** Google (Firebase, Google AI) and Supabase (AWS infrastructure) process data in the U.S.
- **European Union:** Supabase offers EU-based infrastructure options.
- **Other Regions:** Depending on configuration and load balancing.

### 7.1 Safeguards for International Transfers
- **Standard Contractual Clauses (SCCs):** Our service providers use SCCs approved by the European Commission to ensure adequate data protection.
- **GDPR Compliance:** Supabase and Google have implemented measures to comply with GDPR requirements for international data transfers.
- **Privacy Shield:** While Privacy Shield has been invalidated, our providers use alternative mechanisms like SCCs and Binding Corporate Rules.

### 7.2 Your Rights
If you are in the EEA, UK, or Switzerland, you have the right to object to international data transfers. However, this may limit or prevent your ability to use the Service.

---

## 8. Your Rights and Choices

Depending on your location, you may have the following rights regarding your personal data:

### 8.1 Access and Portability
- **Access:** You can view and access your data (lists, items, groups, friends, feedback) directly within the App.
- **Portability:** You can request a copy of your data in a structured, machine-readable format (e.g., JSON) by contacting us at support@listist.app.

### 8.2 Correction
- **Edit Data:** You can update lists, items, groups, friends, and settings directly in the App.
- **Account Info:** Update your Google account information through Google; changes will reflect in the App upon re-authentication.

### 8.3 Deletion
- **In-App Deletion:** Use Settings > Data Management to delete your account and all associated data.
- **Request Deletion:** Contact us at support@listist.app to request data deletion. We will respond within 30 days (or as required by law).
- **Anonymous Data:** Delete the App or use the in-app data reset tool to remove local guest data.

### 8.4 Objection and Restriction
- **Object to Processing:** You can object to certain processing activities (e.g., analytics, AI features) by disabling them in Settings or contacting us.
- **Restrict Processing:** You can request that we restrict processing of your data in certain circumstances (e.g., while we verify accuracy).

### 8.5 Withdraw Consent
- **Push Notifications:** Disable push notifications in App Settings or device OS settings. This will remove your FCM token from our database.
- **AI Features:** Simply stop using AI-powered features. You can also request deletion of your AI cache.
- **Analytics:** Analytics can be disabled in debug builds. In production, data is aggregated and anonymized.

### 8.6 Lodge a Complaint
- **Supervisory Authority:** If you are in the EEA, UK, or Switzerland, you have the right to lodge a complaint with your local data protection authority.
- **Contact Us First:** We encourage you to contact us first so we can address your concerns directly.

### 8.7 Do Not Sell My Personal Information (CCPA)
- **California Residents:** We do NOT sell your personal information. You have the right to request information about data we collect, use, and disclose. Contact us at support@listist.app.

### 8.8 Automated Decision-Making
- **AI Suggestions:** Our AI features provide suggestions, but you are not subject to automated decision-making that significantly affects you. All AI outputs are optional recommendations that you can accept or reject.

---

## 9. Children's Privacy

The Service is **not intended for children under the age of 13** (or the applicable age of digital consent in your jurisdiction).

- **No Knowing Collection:** We do not knowingly collect personal information from children under 13.
- **Parental Consent:** If you are under 18, you must have parental or guardian consent to use the Service.
- **Discovery:** If we discover that we have collected data from a child under 13 without parental consent, we will delete that data promptly.
- **Report:** If you believe we have inadvertently collected data from a child under 13, please contact us immediately at support@listist.app.

---

## 10. Third-Party Links

The App may contain links to third-party websites or services (e.g., URLs attached to list items):

- **External Sites:** Clicking these links will take you outside the App. We are not responsible for the privacy practices or content of third-party sites.
- **Review Policies:** We encourage you to review the privacy policies of any third-party sites you visit.
- **No Endorsement:** The presence of a link does not imply our endorsement of that site or service.

---

## 11. Changes to This Privacy Policy

We may update this Privacy Policy from time to time to reflect changes in our practices, legal requirements, or the Service itself.

### 11.1 Notification
- **In-App Notice:** We will notify you of material changes through the App (e.g., a banner or announcement).
- **Email Notification:** We may also notify you via email if we have your email address.
- **Effective Date:** The "Last Updated" date at the top of this policy will be updated to reflect the latest version.

### 11.2 Review
- **Periodic Review:** We encourage you to review this Privacy Policy periodically.
- **Continued Use:** Your continued use of the Service after changes become effective constitutes acceptance of the updated Privacy Policy.

### 11.3 Material Changes
If we make material changes that significantly affect your rights, we will:
- Provide prominent notice in the App
- Request your consent if required by law
- Give you the option to delete your account if you do not agree

---

## 12. Contact Us

If you have any questions, concerns, or requests regarding this Privacy Policy or our data practices, please contact us:

### Email
**listist-legal@gmail.com**

### In-App Feedback
You can also submit questions or concerns through the App's feedback system (Settings > Send Feedback).

### Response Time
We will respond to your inquiry within **30 days** (or as required by applicable law, such as 45 days under CCPA).

### Data Protection Officer
For GDPR-related inquiries, you may contact our Data Protection Officer at: **privacy@listist.app** (if applicable).

---

## 13. Additional Information for Specific Jurisdictions

### 13.1 European Economic Area (EEA), United Kingdom, Switzerland
- **GDPR Rights:** You have the rights outlined in Section 8, including access, correction, deletion, portability, objection, and restriction.
- **Legal Basis:** We process your data based on contract performance, legitimate interests, consent, and legal obligations (see Section 3).
- **Data Transfers:** We use Standard Contractual Clauses for international data transfers (see Section 7).
- **Supervisory Authority:** You can lodge a complaint with your local data protection authority if you believe we have violated your rights.

### 13.2 California (CCPA)
- **Right to Know:** You can request information about the categories and specific pieces of personal information we collect, use, and disclose.
- **Right to Delete:** You can request deletion of your personal information, subject to certain exceptions.
- **Right to Opt-Out:** We do not sell personal information, so there is no need to opt out.
- **Non-Discrimination:** We will not discriminate against you for exercising your CCPA rights.
- **Contact:** Email support@listist.app to exercise your rights.

### 13.3 Other Jurisdictions
If you are located outside the EEA, UK, Switzerland, or California, you may still have rights under local privacy laws. Contact us to learn more.

---

## 14. Data Processing Summary

For transparency, here is a summary of data we collect and process:

| Data Type | Purpose | Legal Basis | Retention | Third Parties |
|-----------|---------|-------------|-----------|---------------|
| Google Account Info | Authentication, profile | Contract, Consent | While account active | Google |
| Lists & Items | Core functionality | Contract | While account active | Supabase |
| Collaboration Data | Sharing, invitations | Contract, Consent | While account active | Supabase, Google (email) |
| Friends | Quick collaboration | Legitimate Interest | While account active | Supabase |
| Feedback | Service improvement | Consent | Indefinitely (anonymized) | Supabase |
| FCM Tokens | Push notifications | Consent | While notifications enabled | Firebase |
| Analytics | Service improvement | Legitimate Interest | 60-90 days (aggregated) | Firebase |
| Crash Reports | Bug fixing | Legitimate Interest | 60-90 days | Firebase |
| AI Prompts & Responses | AI features | Consent | 90 days (cached) | Google AI, Supabase |
| IP Address | Security, fraud detection | Legitimate Interest | 30 days (logs) | Supabase |

---

## 15. Consent

By using Listist, you acknowledge that you have read, understood, and agree to this Privacy Policy.

- **Acceptance:** Continued use of the Service constitutes acceptance.
- **Withdraw Consent:** You can withdraw consent for optional features (AI, notifications) at any time through Settings.
- **Decline:** If you do not agree with this Privacy Policy, please discontinue use of the Service and delete your account.

---

## 16. Conclusion

At Listist, we are committed to protecting your privacy and being transparent about our data practices. We believe in:
- **Privacy by Design:** Building privacy protections into our Service from the ground up.
- **Data Minimization:** Collecting only the data necessary to provide and improve the Service.
- **User Control:** Giving you control over your data and privacy settings.
- **Transparency:** Being clear and honest about our practices.

Thank you for trusting Listist with your data. We're here to help you organize your life, beautifully and securely.

---

**Last Updated:** October 11, 2025  
**Effective Date:** October 20, 2025

**© 2025 Listist. All rights reserved.**