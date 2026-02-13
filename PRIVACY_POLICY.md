# Privacy Policy

**Last Updated: February 13, 2026**

## Introduction

This Privacy Policy describes how your personal information is collected, used, and shared when you use the COMPA.ai app ("the App"). COMPA.ai is a recovery companion app that handles **sensitive health-related information** including addiction recovery data. We are deeply committed to protecting your privacy.

## Information We Collect

### Information You Provide

- **First Name**: If you choose to share your name with the AI companions, it is stored locally on your device. Your first name is also sent to our AI service to personalize responses (see "AI Conversations" below).
- **Sobriety Date**: Your sobriety start date is stored locally on your device only.
- **Chat Messages**: Conversations with AI companions (Jennifer, Bob, Marcus, Alex, and Maria) are stored locally on your device.
- **Journal Entries**: Diary entries, morning pledges, and evening reviews are stored locally on your device.
- **Trigger Selections**: Your craving trigger tracking data is stored locally on your device.
- **Budget Data**: Financial tracking entries are stored locally on your device.
- **MP3 Files**: Audio files you import are stored in the app's local documents folder on your device.
- **Language Preference**: Your selected language (English or Spanish) is stored locally on your device.
- **Community Forum Data**: If you choose to join the Community forum, your chosen nickname, forum posts, and direct messages are stored on our Supabase server. See "Community Forum" below.

### Information Collected Automatically

**None.** This app does not automatically collect analytics, crash reports, device identifiers, or any other data from your device.

### Device Permissions

The App may request the following permissions:

- **Notifications**: Used to send local reminders for morning pledges, evening reviews, and AI companion check-ins. All notifications are scheduled and triggered locally on your device — no remote push notification servers are involved.
- **Background Audio**: Used to continue music playback when the App is in the background.
- **Microphone**: Required only if you use voice chat with AI companions. Audio is processed on-device by Apple's Speech framework or sent to ElevenLabs for text-to-speech (see "Third-Party Services" below). We do not record or store your audio.
- **Speech Recognition**: Used to convert your voice to text when speaking to AI companions. Speech recognition is processed by Apple's on-device Speech framework.

### Information Processed by Third Parties

- **AI Conversations**: When you chat with AI companions, your messages, conversation history (last 6 messages), and first name (if provided) are sent to our secure server to generate responses. Messages are processed in real-time and **immediately discarded** — we do not store your conversations on our servers.
- **Voice Synthesis**: When text-to-speech is enabled, the AI companion's text response is sent to ElevenLabs through our Supabase server to generate spoken audio. This feature is included with all subscription tiers. The text is processed in real-time and is not stored. No user voice data is sent to ElevenLabs — only the AI's text output.
- **Community Forum**: Forum posts, nicknames, and direct messages are stored on our Supabase server to enable the community feature. You may delete your posts at any time.

## Sensitive Health Information

This App handles information related to addiction recovery, including sobriety dates, substance use indicators, craving triggers, mood data, and journal entries about recovery. We treat all of this as **sensitive health information**:

- All health-related data is stored **exclusively on your device**
- Health data is **never transmitted** to any server (except AI chat messages, which are immediately discarded after generating a response)
- Health data is **never sold, shared, or used for advertising**
- Community forum posts are user-initiated and voluntary — we recommend not sharing personally identifiable health details in public forum posts

## How We Use Your Information

We use the information solely to:

- Provide and maintain the App's functionality
- Generate personalized AI companion responses
- Generate AI companion voice responses (when realistic voice is enabled)
- Display your sobriety progress and milestones
- Send local reminder notifications for journaling
- Enable community forum interactions between users

## Data Storage

**All personal recovery data is stored locally on your device.** Community forum data is stored on our Supabase server. Specifically:

| Data | Storage Location |
|------|-----------------|
| Sobriety dates | UserDefaults (on device) |
| AI chat history | UserDefaults (on device) |
| Journal / Pledge / Review entries | UserDefaults (on device) |
| Trigger tracking | UserDefaults (on device) |
| Budget data | UserDefaults (on device) |
| First name | UserDefaults (on device) |
| Language preference | UserDefaults (on device) |
| Mood tracking | UserDefaults (on device) |
| MP3 files | App Documents folder (on device) |
| Forum posts & DMs | Supabase server (encrypted in transit) |
| Forum nickname | Supabase server & UserDefaults (on device) |

**Note on Backups**: Data stored on your device may be included in iCloud or local iTunes/Finder backups according to your device's backup settings. These backups are managed by Apple and are subject to [Apple's Privacy Policy](https://www.apple.com/privacy/).

**Account**: The App does not require a traditional account with email/password for its core features. The Community forum uses anonymous authentication through Supabase — only a chosen nickname is required. We do not collect email addresses, phone numbers, or government-issued identifiers.

## In-App Purchases

COMPA.ai subscriptions (Starter, Basic, Plus, and Premium tiers) are processed entirely by Apple through StoreKit. We do not collect or have access to your payment information (credit card numbers, billing address, etc.). Subscription status is verified locally on your device through Apple's transaction system. Please refer to [Apple's Privacy Policy](https://www.apple.com/privacy/) for how Apple handles payment data.

## Third-Party Services

The App uses the following third-party services:

| Service | Purpose | Data Sent |
|---------|---------|-----------|
| **Supabase** | Secure API routing for AI chat; community forum hosting | Chat messages and first name for AI (processed in real-time, not stored); forum posts and nicknames (stored) |
| **DeepSeek** | AI language model processing | Chat messages (processed in real-time, not stored) |
| **ElevenLabs** | AI voice synthesis (all subscription tiers) | AI companion text responses for voice generation (processed in real-time, not stored). No user audio or personal data is sent. |
| **Apple StoreKit** | Subscription management | Managed entirely by Apple |
| **Apple Speech Framework** | On-device speech recognition | Voice audio processed locally on device by Apple |

These services have their own privacy policies:
- [Supabase Privacy Policy](https://supabase.com/privacy)
- [DeepSeek Privacy Policy](https://www.deepseek.com/privacy)
- [ElevenLabs Privacy Policy](https://elevenlabs.io/privacy)
- [Apple Privacy Policy](https://www.apple.com/privacy/)

## Data Sharing

We do **not** sell, trade, or transfer your personal information to third parties. Your data stays on your device except:

- AI chat messages and your first name (if provided) are transmitted to generate AI responses and are **immediately discarded** after processing
- AI companion text responses are transmitted to ElevenLabs for voice synthesis when text-to-speech is enabled (included with all subscription tiers), and are **immediately discarded** after audio is generated
- Community forum posts, nicknames, and direct messages are stored on our Supabase server to facilitate the community feature

## Data Security

- All data on your device is stored using Apple's secure sandboxed storage mechanisms
- AI chat messages and voice synthesis requests are encrypted in transit using HTTPS/TLS
- The DeepSeek and ElevenLabs API keys are stored server-side (Supabase Edge Functions) and are never exposed to the client app
- Community forum data is transmitted and stored using Supabase's encrypted infrastructure
- No personal recovery data is stored on our servers

## Children's Privacy

The App is not intended for use by children under the age of 17 due to its subject matter (addiction recovery). We do not knowingly collect personal information from children.

## Your Rights

You have the right to:

- **Delete All Data**: Clear all data by deleting the App from your device
- **Delete Specific Data**: Use in-app reset/delete options for individual features (clear chat history, delete diary entries, etc.)
- **Revoke Data Consent**: Revoke AI data-sharing consent at any time within the app, which will disable AI chat features while keeping all other features available
- **Revoke Permissions**: Revoke microphone, speech recognition, or notification access at any time through iOS Settings → COMPA.ai
- **Opt Out of Name Sharing**: You can choose not to provide your name to AI companions
- **Delete Forum Content**: Delete your community forum posts at any time
- **Full Control**: All recovery data is on your device — you have complete control over it at all times

## Data Portability

Since all recovery data is stored locally on your device, it is included in your standard iCloud or iTunes/Finder backups. The App does not currently offer a standalone data export feature.

## Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be posted with an updated "Last Updated" date. Continued use of the App after changes constitutes acceptance of the revised policy.

## Contact Us

If you have questions about this Privacy Policy or wish to exercise your data rights, please contact us at:

**Email**: normaldude99@yahoo.com

---

## Compliance

This App complies with:
- Apple App Store Guidelines (including Guidelines 5.1.1 and 5.1.2 — Data Collection, Storage, and Use)
- General Data Protection Regulation (GDPR)
- California Consumer Privacy Act (CCPA)

---

*By using the App, you agree to the collection and use of information in accordance with this Privacy Policy.*
