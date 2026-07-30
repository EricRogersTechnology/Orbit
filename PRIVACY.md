# Orbit — Privacy Policy

PRIVACY.md: [Español](PRIVACY-es.html)

**Last updated: July 21, 2026**

Orbit (listed on the App Store as **Orbit Dashboard**) is an independent life-dashboard
app. This policy explains what the app does and does not do with your information. The
short version: **Orbit has no account, no ads, and no analytics. The developer operates
no servers and never receives your data.**

Orbit reaches into a lot of your personal information — calendar, reminders, health,
mail, contacts, photos, location. All of it is read on your device, for display on your
dashboard. None of it is sent to the developer.

---

## What we collect

**Nothing is collected by the developer.** Orbit has no user accounts, no sign-in, no
advertising, no third-party analytics or tracking SDKs, and no developer-operated
backend. There is no server of the developer's anywhere in the picture.

## Where your data lives

What you create in Orbit — captures, notes, tasks, projects, journal entries, routines,
settings and dashboard layout — is stored:

- **On your device**, and
- **In your own private iCloud** (Apple CloudKit private database and iCloud
  Key-Value Storage), so it can sync across your iPhone, iPad, Mac, Apple TV, and
  Apple Watch.

iCloud sync uses **your** Apple Account and Apple's infrastructure. It is governed by
[Apple's Privacy Policy](https://www.apple.com/legal/privacy/). The developer has no
access to your iCloud data.

## Information Orbit reads from your device

Each of these is **opt-in** — Orbit asks first, and works without any of them:

- **Calendar and Reminders** — read, and written when you add or complete something.
  These come from Apple's own Calendar and Reminders databases on your device.
- **Health** — activity, sleep, workouts and other metrics you individually enable, read
  from Apple Health. Every metric is off until you turn it on. Orbit reads these for
  display; it does not write your health data anywhere off-device.
- **Contacts** — read live from your address book for the People section, birthdays and
  reconnect nudges. Orbit does not copy your address book into its own storage.
- **Photos** — shown on your Timeline, and saved to your library only when you ask.
- **Location** — "When In Use" only, and only for weather. See below.
- **Microphone and speech recognition** — only while you are dictating a capture. See
  below.
- **HomeKit and Apple Music** — read only if you use those modules.

These stay on your device. Orbit displays them; it does not transmit them.

## Location (used only for weather)

If you use Weather, Orbit asks for **"When In Use"** location access to show local
conditions. Your coordinates are sent to the weather provider to fetch a forecast, and
are **not stored, not linked to your identity, and never used for advertising or
tracking**. The provider is **Open-Meteo** (`open-meteo.com`); the request contains only
a latitude and longitude. If you never use Weather, the app does not request your
location.

## Dictation and on-device intelligence

Capture can parse what you type or dictate into a task, note, idea, quote, or person.
That parsing happens **on your device** using Apple's on-device models.

**Speech-to-text is different and worth being clear about.** Orbit uses Apple's Speech
framework to turn your dictation into text. Depending on your device, language, and
iOS version, Apple may perform that recognition on Apple's servers rather than on the
device. That step is Apple's, governed by
[Apple's Privacy Policy](https://www.apple.com/legal/privacy/) — the developer never
receives your audio or the transcript. If you would rather nothing leave the device,
type your captures instead of dictating them.

## Mail

If you connect email accounts, Orbit talks **directly from your device to your mail
provider** over IMAP/SMTP. There is no mail server of the developer's in between, and
your mail is never copied anywhere else.

**Your mail passwords are stored in the iOS Keychain** — not in a settings file, not in
iCloud documents, and not anywhere the developer can read. For providers that require
them (such as Gmail), use an app-specific password.

Deliveries and travel details are recognised by reading mail **you already have**, on
your device — matching sender domains and tracking numbers. Orbit does **not** contact
carriers, airlines, or booking sites to do it.

## Other services you can connect

All optional, all off until you connect them, and each talks directly from your device:

- **News / RSS** — feeds you add, and **Feedly** (`feedly.com`) if you connect an account.
- **Stocks** — quote data from Yahoo Finance (`query1.finance.yahoo.com`) for the symbols
  on your watchlist.
- **App Store Connect sales** — if you ship apps, Orbit reads your own sales reports from
  `api.appstoreconnect.apple.com` using an API key **you** create and paste in. The key
  is stored in your Keychain.
- **Ring** — if you connect a Ring account for the Garage/Home module.

Credentials for these live in your Keychain. The developer receives nothing from any of
them.

## Network connections the app makes

To summarise, Orbit contacts:

1. **Apple iCloud** — to sync your own data across your own devices.
2. **Your mail provider** — directly, only if you connect an account.
3. **Open-Meteo** — for weather, only if you use it.
4. **Yahoo Finance, Feedly, App Store Connect, Ring** — only if you connect or use them.
5. **RSS feeds you have added.**

There are no other network connections, and no data is sent to the developer or to any
advertiser.

## Face ID

If you turn on App Lock, Orbit uses Face ID (or your device passcode) to protect the
app. Authentication is handled entirely by iOS — **the app never receives your biometric
data**, only a yes-or-no answer from the system.

## Backup and export

Orbit takes automatic snapshots and can export your data to a file that you control.
Those files are created on your device and go wherever you choose to put them — the
developer never receives them.

## In-app purchases

Any purchase is processed entirely by **Apple's App Store**; the developer receives only
Apple's standard sales reports and **never** sees your payment details.

## Children

Orbit is not directed to children and collects no personal information from anyone.

## Changes to this policy

If this policy changes, the updated version will be posted here with a new "Last
updated" date.

## Contact

Questions about privacy? Contact: **Eric@EricRogersTechnology.com**
