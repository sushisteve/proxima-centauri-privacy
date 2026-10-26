# Proxima Centauri — Privacy Policy

**Effective date:** 2026-10-23
**Last updated:** 2026-10-23

Proxima Centauri (the "App") is a missed-connections app that uses Bluetooth
Low Energy (BLE) to help you remember people you've crossed paths with. This
Privacy Policy explains what information the App collects, why, how it is
stored, and the choices you have about it.

**Short version:** We require no email, phone number, or real name to use the
App. Your identity in the system is a randomly generated identifier, not
anything that can be linked to you by itself. We do not sell, rent, or share
your data with advertisers, data brokers, or analytics services.

---

## 1. Information You Choose to Provide

The App asks you for only two pieces of information to function:

- **An alias** — a short handle of your choosing (letters, spaces, and up to
  two emojis from a curated list). Phone numbers and digits are not
  permitted. You decide whether your alias reveals anything about who you
  are. If you choose a nickname rather than your legal name, nothing in the
  App's technical design will connect it back to you.
- **A photo** — an image you choose to represent yourself to nearby users. You
  decide whether to use a selfie, a drawing, a pet photo, or anything else.
  The image is downsized to 512×512 pixels before it leaves your device.

Everything else about identity is generated automatically and anonymously.

## 2. Information Generated Automatically

When you first launch the App, a few things happen in the background:

- **A random identifier (UUID)** is created for you by our authentication
  provider (Supabase). This identifier is a string of random letters and
  numbers; it does not contain your name, email, phone number, Apple ID, or
  any other personal detail. We refer to this throughout as "your UUID."
- **An encryption keypair** is generated on your device and stored securely
  in the iOS Keychain. The public key is uploaded to the server so other
  users can send you encrypted messages. The private key never leaves your
  device.
- **A credit balance record** is created on the server, keyed only to your
  UUID.

We do **not** collect:
- Your Apple ID or iCloud account information
- Your device's MAC address, IMEI, serial number, or advertising ID (iOS
  does not permit apps to access these in the first place)
- Your contacts, calendar, call history, SMS, or photo library (beyond the
  single photo you explicitly pick for your profile)
- Any analytics, usage telemetry, crash reports with personal data, or
  behavior tracking of any kind
- Any third-party tracking SDK output — the App contains no advertising or
  analytics SDKs

## 3. Information Generated During Use

As you use the App, the following data is created and associated with your
UUID:

- **Bluetooth sightings of other users.** When you cross paths with another
  App user, your device records a timestamped sighting using their UUID.
  Only after sustained proximity (5 one-minute windows of signal within a
  12-minute period, or the other user activating a "boost" feature) does the
  encounter become a "discovery" visible in your app.
- **Location at the moment of discovery.** If you have granted the App
  location permission, the latitude and longitude at the moment of each
  discovery is recorded. This location data is stored on your device only; it
  is never uploaded to our servers.
- **Encounter location pins.** Additional location pins recording where you
  crossed paths with discovered users (used for your personal "Log" map).
  Also stored on your device only.
- **Connection requests.** If you ask to connect with someone, a record is
  created on the server containing both UUIDs and the short subject line you
  entered. Subject lines are limited to 18 characters and cannot contain
  digits, to prevent misuse (e.g., smuggling a phone number).
- **Chat messages.** If you spend a credit to start a chat, the messages
  exchanged are stored on the server, associated only with UUIDs.
- **Ghost / block list.** If you choose to permanently block another user,
  that choice is recorded on the server to enforce it across both devices.
- **Credit purchases.** When you buy credits through the App Store, Apple
  provides us with a transaction receipt that we validate. We store a record
  of the transaction (your UUID, the pack purchased, timestamp) for audit
  purposes. We do not receive your payment card information at any point —
  Apple handles payment processing entirely.
- **Reports and bans.** If you report another user's alias or receive a ban,
  the moderation record (your UUID, the other user's UUID, the reason, the
  timestamp) is retained for safety-review purposes.

## 4. How Information Is Used

The information above is used solely to make the App work:

- Your UUID identifies you to the server and to other users of the App.
- Your alias and photo are shown to users physically near you so they can
  recognize you.
- Your sightings and discoveries let you remember people you've crossed
  paths with.
- Your location pins populate your personal encounter map.
- Credit records enforce the economic model of the App.
- Moderation records allow us to take action against abusive users.

We do not use your information for advertising, profiling, marketing to
you, or sale to third parties.

## 5. How Information Is Stored and Shared

- All data uploaded to our servers is transmitted over HTTPS (TLS 1.2 or
  higher).
- Our server infrastructure is operated by **Supabase, Inc.**
  (<https://supabase.com>), a third-party cloud provider based in the United
  States. Supabase acts as our data processor and does not use your data
  for any purpose other than hosting our database. Their privacy practices
  are described at <https://supabase.com/privacy>.
- Apple handles IAP payment processing. We never see your payment card
  information.
- We do not share your data with advertisers, data brokers, or any other
  third party.

## 6. Data Retention

- **Chat messages** are automatically deleted from our servers 30 days after
  they are sent.
- **Connection requests** (declined or completed) are deleted 90 days after
  they are issued; abandoned pending requests are deleted after 30 days.
- **Dismissed reports** are deleted 90 days after dismissal.
- **Lifted bans** are deleted one year after they were originally issued.
- **UUIDs, aliases, public keys, blocks, and active bans** are retained for
  as long as your account exists.

## 7. Your Choices

- **Change your alias and photo** at any time from the Profile tab.
- **Set exclusion zones** that pause your discoverability within specific
  geographic areas.
- **Block ("ghost") any other user** permanently.
- **Delete your account.** To delete your data entirely, uninstall the App
  and email the address below asking us to erase the UUID associated with
  your device. We will delete your record from our database within 30 days
  of a verified request.

## 8. Children's Privacy

Proxima Centauri is not directed at children under 13. We do not knowingly
collect information from anyone under 13. If you believe a child has used
the App, please contact us and we will delete the information.

## 9. International Users

The App's servers are located in the United States. By using the App you
consent to the transfer of your data to the United States. If you are
located in the European Economic Area (EEA), the United Kingdom, or
California, you have rights to access, correct, delete, or port your data —
please contact us using the address below to exercise these rights.

## 10. Changes to This Policy

We may update this Privacy Policy from time to time. If we make a material
change, we will post the new policy here and update the "Last updated" date
at the top. For significant changes, we will notify active users through
the App.

## 11. Contact Us

Questions, requests for data access or deletion, or complaints about this
Privacy Policy can be sent to:

**sushisteve@icloud.com**
