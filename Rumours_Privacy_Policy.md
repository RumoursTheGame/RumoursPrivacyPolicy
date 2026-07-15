# Rumours — Privacy Policy

Effective 28 April 2026 · Version 1.0

This Privacy Policy explains how **Hugo Murutar**
collect and process personal data when you use the mobile application
"**Rumours**" (the "**App**"). It is written to comply with the EU
General Data Protection Regulation (GDPR), the Estonian Personal Data
Protection Act, the California Consumer Privacy Act / California Privacy
Rights Act (CCPA/CPRA) and the Children's Online Privacy Protection Act
(COPPA).

## 1. Who We Are

**Hugo Murutar.

Country: Estonia.

Privacy contact:
rumoursfeedback@gmail.com

## 2. Summary at a Glance

In plain language:

-   The App **does not** require an account, name or email to play.

-   The App generates a random **anonymous device identifier** (a UUID)
    on first launch.

-   The App sends **anonymous gameplay statistics** (no player names, no
    answers, no story text) to our analytics backend after each game.

-   If you choose to fill in our optional in-game **feedback form**, we
    receive your ratings and any free-text comment you write (up to 280
    characters).

-   Player names, answers, custom prompts and assembled stories **stay
    on your device** and on the devices you play with locally over
    Bluetooth or Wi-Fi.

-   We **do not** collect your real name, email, contacts, location,
    photos, microphone or advertising identifier.

-   We **do not track you** across other apps or websites and we **do
    not sell or share** your personal information.

## 3. What Data We Process

### 3.1 Information stored only on your device

The following information is stored locally on your device by iOS and is
not transmitted by us:

-   **Player names, answers, custom prompts and assembled stories** you
    create during gameplay.

-   **Local game logs** (a JSON file per session in the App's sandboxed
    Documents directory) for in-app history.

-   **App settings** such as the text-size preference and the show-hints
    toggle.

-   **A buffered queue of analytics events** awaiting transmission,
    cleared once delivery is confirmed.

Uninstalling the App removes this data from your device.

### 3.2 Information transmitted to our analytics backend

After each gameplay session (or immediately on abandon), the App sends a
single JSON payload to our analytics backend hosted on Supabase. The
payload contains:

-   A randomly generated anonymous **device identifier (UUID)** stable
    to this install of the App;

-   A **session sequence number** per device (1, 2, 3 ...);

-   A **randomly generated session ID** (UUID);

-   App version, device model (e.g. "iPhone15,3"), and locale region
    (e.g. "EE", "US");

-   Game mode, scenario name, scenario mode (classic / different /
    custom), timer mode, player count;

-   Session duration in seconds, total prompt count, prompts completed,
    completion flag, abandon screen and abandon prompt index (if
    applicable);

-   Acquisition source — a free-text tag captured from a
    **rumours://** deep link if you opened one (e.g. "poster\_001"),
    used to understand which marketing channels work.

**We do not transmit** player names, free-text answers, custom prompts,
or assembled stories to our backend. They never leave the participating
devices through this analytics flow.

### 3.3 Optional feedback form

After your first completed game, the App offers a one-time feedback
form. If — and only if — you submit it, we receive:

-   Three emoji ratings (1–4) about whether the story made you laugh,
    whether you would play again, and whether you would recommend the
    App;

-   Two short choices (e.g. "Yes / A bit / No") about whether anything
    was confusing and whether the game made sense;

-   An optional free-text comment of up to 280 characters;

-   The session ID, device ID, locale region, app version and
    acquisition source so we can correlate feedback with the
    corresponding session row.

**Please do not type personal data (name, email, address, phone) into
the comment field.** If you do, we will treat it as personal data and
you may ask us to delete it at any time using the contact details below.

### 3.4 Multiplayer / local connectivity

When you play multiplayer, your device exchanges game data directly with
nearby devices over **Bluetooth Low Energy** or, where available,
**local Wi-Fi (Multipeer Connectivity)**. iOS will prompt you for
Bluetooth permission. The traffic stays between the participating
devices in the same physical space and **does not pass through our
servers**. We do not log or store the contents of multiplayer messages.

### 3.5 Data we explicitly do not collect

-   Real name, email address, phone number, postal address.

-   Precise or coarse location.

-   Camera, photo library, microphone, contacts, calendars, health,
    motion data.

-   Apple's IDFA / advertising identifier or any cross-app tracking
    identifier.

-   Web-browsing history or activity in other apps.

Because the App does not *track* you across other companies' apps and
websites, we do not present an **App Tracking Transparency** (ATT)
prompt.

## 4. Why We Process This Data and Legal Bases

Under GDPR, our legal bases are:

-   **Legitimate interest** (Article 6(1)(f) GDPR) — to operate,
    secure and improve the App through anonymous gameplay statistics. We
    have weighed this against your privacy and consider it proportionate
    because the data is anonymous and minimal.

-   **Consent** (Article 6(1)(a) GDPR) — when you actively submit the
    optional feedback form.

-   **Performance of a contract / pre-contractual measures** (Article
    6(1)(b) GDPR) — to provide the App in line with our Terms of
    Service.

-   **Legal obligation** (Article 6(1)(c) GDPR) — where applicable, to
    comply with law.

## 5. Sub-Processors and Recipients

We use the following processors. We do not sell or rent personal data to
anyone.

-   **Supabase** — hosts our analytics and feedback database
    (PostgreSQL accessed over HTTPS REST). Hosting region: \[Supabase
    hosting region — confirm before publishing\]. Supabase processes
    data on our behalf under a data-processing agreement.

-   **Apple Inc.** — distributes the App via the App Store and
    provides device-level services. Apple may receive certain limited
    information at the platform level (e.g. crash reports, App Store
    statistics) under [[Apple's privacy
    policy]{.underline}](https://www.apple.com/legal/privacy/),
    independent of us.

## 6. International Data Transfers

Where data is processed by our sub-processors outside the European
Economic Area (EEA), we rely on appropriate safeguards under Articles
44–49 GDPR, in particular the European Commission's **Standard
Contractual Clauses**, and we choose hosting regions that minimise
transfers where reasonable.

## 7. Retention

-   **Anonymous session events** are retained on our backend for up to
    **24 months** from receipt, then deleted or aggregated.

-   **Feedback events** are retained for up to **36 months** from
    receipt.

-   **Local game logs and settings** remain on your device until you
    delete the App or clear its data.

-   **The on-device analytics buffer** is cleared automatically as soon
    as transmission to the backend is confirmed.

## 8. Security

All transmissions to the analytics backend use **HTTPS / TLS**. Server
access is restricted via Supabase API keys and database row-level
security. We design the App so that **the data we receive is anonymous
by default** — the practical and most effective security control.

No system is perfectly secure. If a breach affecting your personal data
occurs, we will notify the relevant supervisory authority and, where
required, affected users in line with GDPR Articles 33–34.

## 9. Your Rights

### 9.1 Rights under GDPR (EU/EEA/UK users)

You have the right to:

-   **Access** the personal data we hold about you;

-   **Rectify** inaccurate data;

-   **Erase** your data ("right to be forgotten");

-   **Restrict** or **object to** processing based on legitimate
    interest;

-   **Data portability** — receive your data in a structured
    machine-readable format;

-   **Withdraw consent** at any time (e.g. for feedback) without
    affecting prior lawful processing;

-   **Lodge a complaint** with a data-protection supervisory authority
    — in Estonia, the **Andmekaitse Inspektsioon (Estonian Data
    Protection Inspectorate)**,
    [aki.ee](https://www.aki.ee/).

To exercise these rights, email
rumoursfeedback@gmail.com.

Because we don't hold your name or email, we identify your data through
the **anonymous device ID** the App generates. The device ID can be
found in the App under **Settings → About**. Without it we may be unable
to locate your data.

### 9.2 Rights under CCPA/CPRA (California users)

-   Right to know what personal information we collect, use and
    disclose;

-   Right to delete personal information;

-   Right to correct inaccurate personal information;

-   Right to opt out of sale or sharing — note that we **do not sell
    or share** personal information;

-   Right to non-discrimination for exercising your privacy rights.

## 10. Children's Privacy

The App is intended for users aged **13 and older**. We do not knowingly
collect personal data from children under 13 (**COPPA**). If you believe
a child under 13 has provided data through the App, contact us at
rumoursfeedback@gmail.com and we will delete it.

In the European Union, in countries where the GDPR digital-services age
of consent is set higher than 13 (up to 16), parental consent is
required for users under that age to submit the optional feedback form.
Anonymous gameplay analytics are minimal and based on legitimate
interest.

## 11. Choices and Controls

-   **Bluetooth permission** can be revoked any time in iOS Settings →
    Bluetooth → Rumours.

-   **Analytics** can be disabled by deleting the App. (We aim to add an
    in-app analytics opt-out toggle in a future version.)

-   **Feedback** is opt-in; not submitting the form means no feedback
    data is sent.

-   **Local data** is removed by deleting the App from your device, or
    by clearing its data via iOS Storage settings.

## 12. Changes to this Policy

We may update this Privacy Policy as the App evolves or as legal
requirements change. The current version and effective date are shown at
the top of this document and inside the App. Material changes will be
highlighted in the App.

## 13. Contact

If you have questions, complaints or requests:

**Hugo Murutar**

Estonia

Email:
rumoursfeedback@gmail.com

Support:
rumoursfeedback@gmail.com

*This Privacy Policy was last updated on 28 April 2026. It is not legal
advice and should be reviewed by qualified counsel before publication.*
