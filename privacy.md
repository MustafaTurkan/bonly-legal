---
title: Privacy Policy — Bonly
permalink: /privacy/
---
<!-- Source: docs/legal/privacy_policy_en.md -->

[← Bonly]({{ '/' | relative_url }}) · Türkçe: [Aydınlatma Metni]({{ '/tr/aydinlatma/' | relative_url }}) · [Gizlilik Politikası]({{ '/tr/gizlilik/' | relative_url }})

# Bonly — Privacy Policy

**Version 1 · Effective: 24 October 2026 · Last updated: 24 October 2026**

This policy applies to users in all countries. For users in Türkiye, the Turkish KVKK
[Information Notice (Aydınlatma Metni)]({{ '/tr/aydinlatma/' | relative_url }}) and
[Explicit Consent Texts (Açık Rıza Metinleri)]({{ '/tr/acik-riza/' | relative_url }}) also apply; where this policy and the
KVKK notice differ for a user in Türkiye, the KVKK notice prevails. Part B contains regional supplements.

## Part A — Global policy

### 1. Who we are (controller)

Mustafa Türkan, an individual developer based in Türkiye ("we", "us"), is the controller of the personal data processed
through the Bonly mobile app (the "App"). Contact: [mustafatrkn93@gmail.com](mailto:mustafatrkn93@gmail.com). You can contact
us for any privacy matter at [mustafatrkn93@gmail.com](mailto:mustafatrkn93@gmail.com). Representatives outside Türkiye:
see Part B.

### 2. Summary

- We process the expense and budget data **you enter** only to provide the App to you. **No ads, no sale of personal data,
  no tracking** (no IDFA / advertising ID, no cross-app tracking).
- On most receipts the photo is read **on your phone** and only the text is sent. If a receipt cannot be read on the phone
  (unsupported script or low reading quality) and you have given AI consent, the receipt photo — with location and other
  metadata removed — is sent to our AI provider; its temporary copy on our server is deleted within 1 day. A photo is stored
  permanently in your own account only if "Keep receipt images" is on.
- AI parsing of receipt, voice or typed expense text and sharing of usage and crash data are **optional**, off by default,
  and each needs your separate consent, which you can withdraw at any time in Settings.
- You can export your data (CSV, or a full ZIP) and delete your account with all its data inside the App.

### 3. Data we process

| Category | Data | When |
| --- | --- | --- |
| Account | Anonymous user ID (uid); name and e-mail only if you link Apple or Google sign-in | On first launch (anonymous); linking is optional |
| Financial data you enter | Expenses (amount, date, category, merchant, note), monthly limit, pay day, income, labels and balances of accounts / cards (only the label you type — never card numbers), budgets, goals, savings jars, recurring payments, warranty / return records, product price history | When you enter it |
| Receipt content | Receipt text (read on your device); the receipt photo if "Keep receipt images" is on; with AI consent, when the receipt cannot be read on the device (unsupported script or low reading quality), a **temporary copy** of the downscaled receipt photo with location and other metadata (EXIF) removed | When you scan a receipt |
| Voice input | Audio never reaches the App or our servers; your phone's speech recognition service (Apple / Google) turns it into text, and the App processes only the text | When you use voice entry |
| Typed expense text | Expense text you type in the smart text field; with AI consent, sent for parsing if it cannot be understood on the device | When you use smart text entry |
| Names of other people | Names you type for shared bills and IOUs (your contacts are never read) | When you enter them |
| Subscription | Subscription status, product, trial / renewal state (payment details stay with Apple / Google) | When you buy Pro |
| Usage and diagnostics (optional) | In-app interactions (events without personal data or amounts), crash and performance logs, app instance / installation IDs | Only if "Share usage and crash data" is on |
| Technical | Push token (FCM), app integrity attestation (App Check), app version, device language and time zone | When you use the App |
| Server logs | IP address, device / app version (user agent), user ID (uid), request time and outcome for requests reaching our servers — for security, abuse prevention and debugging | When you use a server feature (sync, receipt / text parsing, export, etc.) |

We do **not** collect location, contacts, health data, browsing history or advertising identifiers. Face ID / fingerprint
checks happen entirely on your device; no biometric data reaches us. We do not intentionally process special categories of
data (e.g. health, religion); please do not enter such information in free-text notes.

### 4. Purposes and legal bases

| Purpose | Legal basis (GDPR / UK GDPR terms; equivalents in Part B) |
| --- | --- |
| Recording expenses, budgets, daily allowance, period forecast, notifications and reminders, export, account deletion | Performance of a contract (Art. 6(1)(b)) |
| Selling, validating and restoring subscriptions | Performance of a contract (Art. 6(1)(b)) |
| AI parsing of receipt, voice or typed expense **text** — or of the receipt **photo** when the receipt cannot be read on the device — into items and categories (only for entries that cannot be parsed on the device) | **Consent** (Art. 6(1)(a)) — given on the AI consent screen in the App, withdrawable in Settings; without it the App uses on-device parsing only |
| Usage analytics and crash reports (improving the App) | **Consent** (Art. 6(1)(a)) — off by default, switchable in Settings |
| Security, abuse prevention, quotas (App Check, rate limits), server logs | Legitimate interests (Art. 6(1)(f)) in keeping the service secure and affordable |
| Legal obligations; establishing or defending legal claims | Legal obligation (Art. 6(1)(c)); legitimate interests (Art. 6(1)(f)) |

Withdrawing consent does not affect processing carried out before the withdrawal.

### 5. No automated decisions

We do not make decisions based solely on automated processing that produce legal or similarly significant effects on you
(GDPR Art. 22). Category suggestions, the daily allowance and forecasts are calculations you can see and change; they are not
decisions about you.

### 6. Recipients (processors) {#recipients}

We do not sell personal data and do not share it for advertising. We disclose it only to service providers acting on our
instructions (processors / service providers), under data processing terms:

| Recipient | Purpose | Location |
| --- | --- | --- |
| Google Cloud / Firebase (Google Ireland Ltd. / Google LLC) | Database, file storage, server functions, authentication, push notifications, app integrity, remote configuration; with your consent analytics (Google Analytics for Firebase) and crash reports (Crashlytics) | Database and files in the EU (europe-west1, Belgium); some services (Analytics, Crashlytics, FCM) on Google's global infrastructure including the USA |
| RevenueCat, Inc. | Subscription status management | USA |
| Google LLC (Gemini API, paid tier) | AI parsing of receipt, voice or typed expense text, or of the receipt photo (metadata removed) when the receipt cannot be read on the device — only with your consent. No name, e-mail or account ID is sent. The provider processes the input under its applicable terms to return the result; under its paid-tier terms, inputs are not used to train models | USA and other locations of the provider's infrastructure |
| Anthropic, PBC (Claude API) | Same purpose, as an alternative AI provider that may be used for a given request — only with your consent. The provider processes the input under its applicable commercial terms to return the result; under those terms, inputs are not used to train models | USA |
| Apple / Google (as independent controllers) | App stores, payments, optional sign-in linking, on-device / OS speech recognition | Their own privacy policies apply |
| Authorities, courts, professional advisers | Where required by law or to establish / defend legal claims | Where applicable |

### 7. International transfers

We are based in Türkiye and our providers operate in the EU and the USA. Where personal data from the EEA, the UK,
Switzerland or another country with transfer rules is transferred to a country without an adequacy decision, we rely on
appropriate safeguards such as the European Commission's Standard Contractual Clauses (Decision (EU) 2021/914), the UK
International Data Transfer Addendum, adequacy decisions, or the equivalent mechanisms described in Part B (e.g. KVKK
standard contracts for Türkiye, ANPD clauses for Brazil), as applicable. You can request a copy of the relevant safeguards at
[mustafatrkn93@gmail.com](mailto:mustafatrkn93@gmail.com).

### 8. Retention {#retention}

| Data | Period |
| --- | --- |
| Account data and records | Until you delete your account (Settings → Delete account and data; immediate and irreversible) |
| Receipt images | Until you delete the image or the account ("Keep receipt images" can be turned off) |
| Temporary copy of a receipt photo sent for AI parsing (our server) | Deleted when the request completes; at most 1 day after a temporary error |
| Copy at the AI provider | Processed only to return the result; the provider may keep it for a limited period as set out in its terms (for example for abuse monitoring) |
| Records you delete (transactions) | Kept with a "deleted" flag for 30 days so they can be restored; then personal fields (items, merchant, note, receipt text, shared-bill details, labels) are erased and the receipt image deleted; only amount / date / category remain for totals |
| Account-deletion marker | 7 days (user ID only) to complete deletion |
| Exported PDF files (server copy) | 1 day |
| Server request logs (duplicate-request protection) | 7 days |
| Subscription notification records | 30 days |
| Backups | 30 days (deleted accounts leave backups after this period) |
| Server logs (IP address, user agent, uid) | 30 days |
| Analytics / crash data (only with consent) | Analytics 14 months; Crashlytics 90 days |

### 9. Security

Encryption in transit (TLS) and at rest (Google Cloud), server rules limiting access to your own account, app integrity checks
(App Check), optional app lock (Face ID / fingerprint, on device) with content hidden in the app switcher. Sensitive values
such as IBANs are kept only in your device's secure storage.

### 10. Your rights

Depending on where you live (Part B), you may have the right to: access your data; correct it; delete it; restrict or object
to processing (including processing based on legitimate interests); receive your data in a portable format; withdraw consent
at any time; and lodge a complaint with a data protection authority. In the App you can already:

- **export** your data (Settings → Export: CSV; or all data and optional receipt images as a ZIP, link valid for 24 hours);
- **delete** your account and all data (Settings → Delete account and data);
- **withdraw** AI and analytics consent (Settings → Privacy).

For other requests write to [mustafatrkn93@gmail.com](mailto:mustafatrkn93@gmail.com). We answer within one month (GDPR) or
the shorter / longer period required by your local law, free of charge. We may need to verify that the request comes from the
account holder. If you cannot access the App, see [Account deletion without the App](#account-deletion-without-the-app) below.

### 11. Account deletion without the App {#account-deletion-without-the-app}

Send an e-mail with the subject "Account deletion request" to
[mustafatrkn93@gmail.com](mailto:mustafatrkn93@gmail.com). To find and verify your account we will ask you for information
that identifies it (for example, the e-mail address of the Apple or Google account you linked to Bonly); we complete the
request within 30 days. Deleting the account does not cancel a Pro subscription — cancel it in your App Store / Google Play
subscription settings. See also [Delete your account]({{ '/delete-account/' | relative_url }}).

### 12. Children

The App is a personal finance tool and is **not directed to children** under 18 (or the higher age of digital consent in your
country). We do not knowingly collect children's data; if you believe a child has provided data, contact us and we will delete
it. The store age rating (e.g. App Store 4+, Google Play "Everyone") reflects content only (no objectionable content); it does
not mean the App is designed for children.

### 13. Changes

When we change this policy we increase the version number; for material changes the App asks you to review the new version.

## Part B — Regional supplements

These supplements apply in addition to Part A to users in the listed regions, to the extent the relevant law applies to us.

### B.1 European Economic Area, United Kingdom and Switzerland (GDPR / UK GDPR / revFADP)

- **Representatives (GDPR Art. 27 / UK GDPR Art. 27 / revFADP Art. 14):** we are not established in the EU, the UK or
  Switzerland. Where required by law, details of our representative will be published on this page. You can contact us for any
  privacy matter at [mustafatrkn93@gmail.com](mailto:mustafatrkn93@gmail.com).
- **Complaints:** you may lodge a complaint with the supervisory authority of your habitual residence, place of work or
  place of the alleged infringement (EU list: edpb.europa.eu; UK: ICO; Switzerland: FDPIC).
- Legal bases, recipients and transfer safeguards: Part A §4, §6, §7. Children: where we rely on consent for analytics, users
  below the age of digital consent in their member state (13–16) should not enable it.

### B.2 Brazil (LGPD — Law 13.709/2018)

- Legal bases (Art. 7): performance of a contract (V), consent (I) for AI parsing and analytics, legitimate interest (IX) for
  security, compliance with a legal obligation (II).
- **Contact for data protection matters (Art. 41):** you can contact us for any privacy matter at
  [mustafatrkn93@gmail.com](mailto:mustafatrkn93@gmail.com).
- International transfers (Art. 33): ANPD standard contractual clauses or other mechanisms permitted by the LGPD, as
  applicable. Rights (Art. 18) include confirmation, access, correction, anonymisation / blocking / deletion, portability,
  information about sharing, and revoking consent; you may petition the ANPD.

### B.3 United States — California (CCPA / CPRA) and other state privacy laws

- These disclosures are provided for transparency, to the extent these laws apply to us.
- **Categories collected (past 12 months):** identifiers (user ID, device / app instance IDs, optional e-mail), commercial
  information (subscription status), financial information you enter (not account log-in or card numbers), user content
  (receipt text / images, notes), internet / electronic activity (optional analytics, crash logs). Sources: you and your
  device. Purposes: Part A §4. Retention: Part A §8.
- **No sale or sharing:** we do **not sell** personal information and do **not share** it for cross-context behavioural
  advertising, and have not done so in the past 12 months. We therefore do not offer a "Do Not Sell or Share My Personal
  Information" link; Global Privacy Control signals are nonetheless respected because no sale / sharing occurs. We do not use
  or disclose sensitive personal information for purposes requiring a "Limit the Use" link.
- **Rights:** to know / access, delete, correct, and not be discriminated against for exercising them; requests via
  [mustafatrkn93@gmail.com](mailto:mustafatrkn93@gmail.com) or in-app tools; authorised agents may submit requests with proof
  of authorisation. Other states (e.g. Virginia, Colorado, Connecticut, Texas, Oregon): equivalent rights and an appeal
  process — reply to our decision e-mail to appeal.

### B.4 Canada (PIPEDA; Québec Law 25)

You can contact us for any privacy matter, including as the person in charge of the protection of personal information, at
[mustafatrkn93@gmail.com](mailto:mustafatrkn93@gmail.com). Personal information may be stored and processed outside Canada
(EU, USA) and may be accessible to authorities there. Québec residents may request access, rectification and data
portability, and complain to the Commission d'accès à l'information.

### B.5 Australia (Privacy Act 1988, APPs)

Overseas recipients are listed in Part A §6 (EU, USA). You may complain to us first and then to the Office of the Australian
Information Commissioner (OAIC).

### B.6 Japan (APPI)

Personal data is provided to processors in the EU (Belgium) and the USA (Part A §6). Information on the personal data
protection systems of those countries is available from the Personal Information Protection Commission (PPC). Where required,
we obtain your consent to provision to a third party in a foreign country or rely on the recipient's equivalent measures (APPI
Art. 28). Requests for disclosure, correction, suspension of use and deletion:
[mustafatrkn93@gmail.com](mailto:mustafatrkn93@gmail.com).

### B.7 Republic of Korea (PIPA)

Overseas transfer (PIPA Art. 28-8): items transferred — Part A §3; recipients, countries, purposes and retention — Part A §6 and
§8; method — encrypted network transmission at the time of use. You can refuse the transfer by not enabling the optional
features (AI parsing, analytics); core storage on Google Cloud is necessary to provide the service. Data is destroyed by
irreversible deletion when the retention period ends. You can contact us for any privacy matter at
[mustafatrkn93@gmail.com](mailto:mustafatrkn93@gmail.com). Where required by law, details of our domestic representative will
be published on this page.

### B.8 India (Digital Personal Data Protection Act 2023 and DPDP Rules 2025)

We process digital personal data on the basis of your consent or for the legitimate uses permitted by the Act. You may access
a summary of your data, correct and erase it, nominate another person to exercise your rights, and withdraw consent as easily
as you gave it. **Grievances:** you can contact us for any privacy matter at
[mustafatrkn93@gmail.com](mailto:mustafatrkn93@gmail.com); we respond within the period prescribed by the Rules; you may then
approach the Data Protection Board of India. The App is not intended for children (under 18 under the Act); we do not process
children's data or engage in tracking or targeted advertising.

### B.9 Türkiye (KVKK)

The Turkish [KVKK Information Notice]({{ '/tr/aydinlatma/' | relative_url }}) and
[Explicit Consent Texts]({{ '/tr/acik-riza/' | relative_url }}) apply.

### B.10 Other countries

Users in other countries have the rights granted by their local law; contact
[mustafatrkn93@gmail.com](mailto:mustafatrkn93@gmail.com). The App is not currently offered in the mainland China App Store; if
it is offered there in the future, a supplement for the People's Republic of China will be published on this page before then.

## Contact

Mustafa Türkan, Türkiye — [mustafatrkn93@gmail.com](mailto:mustafatrkn93@gmail.com)
