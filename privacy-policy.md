Privacy Policy for فەرهەنگی ناوی کوردی (Kurdish Names Dictionary)

Last updated: 17 November 2025

Kurdish Names Dictionary (“we”, “us”, or “our”) respects your privacy and is designed to collect as little information about you as possible. This Privacy Policy explains what data we collect, how we use it, and what choices you have when you use the Kurdish Names Dictionary mobile application (the “App”).

By using the App, you agree to the practices described in this Policy.

1. Overview

Our main goals are:

to provide a high-quality Kurdish names dictionary,

to understand which names are popular in different languages/locales, and

to do this without tracking individual users or devices.

To achieve this, we only collect:

Anonymous, aggregate usage statistics, and

An optional email address if you choose to contact us and explicitly consent to us using it to reply.

We do not store user IDs, device IDs, advertising IDs, or IP-based location for analytics.

2. Data We Collect
2.1 Anonymous Usage Statistics

We collect anonymous, aggregate counts about how the App is used. For example:

how many times a particular name is liked or shortlisted, and

how many app opens or feature uses occur per locale.

These statistics are stored as counters only, in structures such as:

name_locale_stats/{nameDocId} – total likes/shortlists per locale

app_stats/{yyyyMMdd} – total app opens per locale (if enabled)

We do not store any:

user identifiers,

device identifiers, or

per-event logs tied to an individual.

Multiple actions from the same device only increase aggregate totals; they cannot be traced back to a specific person.

2.2 Locale & Language Information

We use the device’s locale and language (for example, ku_IQ, en_AU) as a proxy for “region” when aggregating the anonymous statistics above.

Locale strings are used only as keys for counters (e.g. “likes of this name in ku_IQ”).

Locale data comes from OS APIs (e.g. PlatformDispatcher.instance.locale), not from IP lookup, GPS, or Wi-Fi.

Locale strings are never stored with any user or device identifier.

2.3 Support Communications (“Contact us”)

If you choose to use the in-app “Contact us” form, we collect:

Message content – whatever you type into the message field (required).

Optional email address – only if you tick a consent checkbox authorising us to use it to reply.

Metadata, such as:

locale (e.g. ku_IQ, en_AU),

app version,

platform (Android/iOS), and

category (e.g. general, bug, suggestion).

This information is stored in a Firestore collection called support_requests.

The email field is only saved when you give explicit consent (“I consent to sharing my email so the Kurdish Names team can reply”).

We do not store any user or device IDs in support_requests.

2.4 Technical Diagnostics (If Enabled)

We may optionally use Firebase Crashlytics or similar tools to collect crash reports and error logs. If enabled, these tools may collect:

device and OS version,

app version, and

technical details about the crash or error.

These diagnostics are used only for debugging and improving app stability. If we disable Crashlytics, this category does not apply.

3. What We Do Not Collect

We intentionally avoid collecting identifying or sensitive data. In particular:

No IP-based geolocation or GPS/Wi-Fi location.

We do not perform public-IP lookups, and we do not store precise location (GPS or Wi-Fi).

No persistent user IDs or device IDs.

We do not create _anonymousId, advertising IDs, or similar identifiers for analytics.

No names, phone numbers, or other personal data, unless you explicitly provide an email address in the support form and consent to its use so we can reply.

All analytics are stored as anonymous, aggregate counters keyed by locale only.

4. How We Use the Data
4.1 Anonymous Usage Statistics & Locale Insights

We use anonymous, aggregate statistics to:

understand which names are popular per locale, and

improve search, ranking, and overall app experience.

Because these statistics are stored only as totals and cannot reasonably be linked to any individual, they are treated as anonymous data and do not fall under the definition of personal data in the GDPR sense.

4.2 Support Communications

We use support data to:

read and triage your message,

reply to you if you provided an email and consented, and

track the status of support requests internally (e.g. open, in progress, closed).

Legal basis: consent – we process your email address only when you explicitly agree (by ticking the checkbox) to let us use it to respond.

4.3 Technical Diagnostics (If Enabled)

If Crashlytics or similar diagnostics are turned on, we use crash reports and logs to:

diagnose issues,

improve stability and performance, and

ensure the App works correctly across devices.

Legal basis: legitimate interest in maintaining and improving the App.

5. Data Sharing & Processors

We do not sell or rent your data.

We use third-party services as processors to operate the App:

Firebase (Google Cloud) for:

Firestore (data storage for aggregate stats and support requests),

Authentication (if used),

Crashlytics (if enabled), and

possibly Firebase Analytics in future releases.

These providers process data on our behalf under their data processing terms and are not allowed to use it for their own independent purposes.

We may disclose data if required by law, regulation, or legal process, or to protect the rights, property, or safety of us, our users, or others.

6. Retention

Our retention rules follow our “minimal data” design:

Anonymous aggregate statistics

Stored indefinitely, as they contain no personal data and cannot be linked to individuals.

Support communications (support_requests)

Kept until we have resolved your issue, plus up to one year.

After that, they are deleted as part of periodic admin reviews (and may in future be automatically removed via Firestore TTL).

Crash logs and diagnostics (if enabled)

Retained according to Firebase Crashlytics defaults, subject to their own data retention policies. We periodically review and adjust these settings as needed.

If you ask us to delete a specific support request that includes your email address, we will delete it sooner where technically feasible.

7. User Choices & Rights

Because analytics are anonymous and do not involve personal data, most data-protection rights arise only in relation to support communications and any other personal data you choose to share (e.g. your email address).

7.1 Sharing Your Email is Optional

You can submit a support message without providing an email.

If you do not tick the consent checkbox, your email will not be stored, and we will not be able to reply — but we can still see the feedback anonymously.

7.2 Access and Deletion

For the support messages that include personal data (your email):

You can ask us to:

confirm whether we hold any support data about you, and

delete that data from our support system.

To do this, contact us using the email address below and include the email address you used in the support form so we can locate the relevant request.

7.3 Objection

If you have concerns about how we handle support data (for example, your email address), you can contact us and object to further processing. We will assess your request and, where applicable, stop processing and delete your support data.

8. Security

We take reasonable measures to protect the data we handle. In particular:

Security Rules: Firestore Security Rules restrict:

aggregate counter updates to controlled paths, and

support_requests read/update access to admin accounts only (identified via custom claims or entries in /admins/{uid}).

Transport & storage:

Data in transit is encrypted using HTTPS/TLS.

Data at rest is encrypted by Firebase by default.

Access control:

We use least-privilege access, 2-factor authentication, and project separation to reduce the risk of unauthorised access.

No method of transmission or storage is 100% secure, but we work to protect data in line with industry practices.

9. International Data Transfers

Firebase and other infrastructure providers may store and process data on servers located outside your country.

Where applicable, these transfers rely on Google’s data-processing commitments and, if relevant, standard contractual clauses or similar safeguards.

10. Children’s Privacy

The App is not directed to children under 16.

We do not knowingly collect personal data (such as email addresses) from children under 16.

If we become aware that we have collected such data without appropriate consent, we will delete it promptly.

If you are a parent or guardian and believe that your child has provided personal data via the support form, please contact us so we can take appropriate action.

11. Changes to This Policy

We may update this Privacy Policy from time to time as the App evolves or legal requirements change.

When we make material changes, we will:

update the “Last updated” date at the top of this page, and

provide a suitable notice in the App (for example, through a banner, dialog, or release notes).

Your continued use of the App after such changes take effect constitutes your acceptance of the updated Policy.

12. Contact Us

If you have any questions about this Privacy Policy or our data practices, or if you wish to exercise your rights regarding support communications, you can contact us at:

Email: kurdishnamesdic@gmail.com
