# Privacy Policy — Netflix Subtitle Tools

**Last updated: 2026-05-06**

## 1. Overview
Netflix Subtitle Tools ("the Extension") is a browser extension that displays and translates subtitles on Netflix's web player. We respect every user's privacy. This document describes what data the Extension processes, how it is processed, and what we never do.

## 2. Information We Collect
The Extension **does not collect any personally identifiable information**. It does not transmit any account credentials, browsing history, cookies, IP addresses, or device information to any server operated by us (we do not operate any backend server).

The Extension stores only the following preference data **locally** on the user's device, so that user preferences persist across Netflix sessions:

- Selected target translation language
- Subtitle display preferences (font size, color, position, etc.)
- Toggle states (translation enabled, show original, etc.)

This data is stored exclusively via Chrome's built-in `chrome.storage.local` / `localStorage` on the user's device. It is never transmitted to any external server and cannot be read by the Extension's developer.

## 3. Third-Party Services
When translation is enabled, the Extension sends the **currently displayed Netflix subtitle text** to Google's public translation endpoint (`https://translate.googleapis.com/translate_a/single`) to obtain a translation. This request is issued directly by the user's browser; it does not pass through any server controlled by us.

- Sent: only the current subtitle text fragment
- Never sent: username, email, Netflix account, watch history, device info
- Third-party privacy policy: https://policies.google.com/privacy

If the user does not enable translation, no external network requests are made.

## 4. Data Sharing & Sale
We **do not sell, trade, or share** any user data with third parties. The Extension contains no advertising, no trackers, and no analytics SDKs.

## 5. Data Retention
All locally stored preference data resides solely on the user's device. Users may delete it at any time by uninstalling the Extension or clearing extension data via Chrome's settings.

## 6. Children's Privacy
The Extension is not directed at children under 13 and does not knowingly collect information from any user.

## 7. Changes to This Policy
Material changes to this policy will be reflected by updating this file in the GitHub repository and noted in the release notes.
