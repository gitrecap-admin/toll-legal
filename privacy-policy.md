# Privacy Policy — Digital Detox

**Last updated: 26 September 2026**

Digital Detox is an iOS app that locks the apps you choose until you earn screen
time back with push-ups, squats, jumping jacks, walking or focused work.

## The short version

> Digital Detox has no account, no advertising, and no server run by us. It does
> not collect your name, your email, your contacts, your photos, your step count
> or the list of apps you block. It does send a small stream of anonymous usage
> events — which screens were reached, whether a purchase succeeded — through a
> privacy-focused analytics service. Those events carry no identifier from your
> device, and nothing in them can be traced back to you by us.

If you read one section below, make it **What Digital Detox sends about how the
app is used**.

## What Digital Detox does not collect

There is no sign-up and no account. Digital Detox never asks for or receives your
name, email address, phone number, contacts, photos, precise location,
advertising identifier, or any other identifier that persists across app
launches.

It also never sends the things it can see on your device: the apps you chose to
block, your step count, camera frames, your coin balance, or your habit history.
Those are covered in the table below and none of them leave your phone.

## What Digital Detox accesses on your device

Each of these is used for one purpose, on your device, and never leaves it
except where explicitly stated further down.

| What | Why | Where it goes |
|---|---|---|
| **Screen Time (Family Controls)** | To shield the apps you pick and unshield them when you spend earned minutes. | Nowhere. iOS never tells Digital Detox which apps you picked — the app only ever holds opaque tokens with no name or bundle identifier attached. |
| **Motion & Fitness — step count (read only)** | To credit screen time for walking you have already done. | Nowhere. Digital Detox asks your iPhone's built-in motion coprocessor (through Apple's Core Motion framework) for today's step total, on the device. It reads nothing earlier than today, stores no step history of its own, and never sends the number anywhere. |
| **Camera** | To count reps with on-device pose detection. | Nowhere. No video or still image is recorded, saved, or transmitted. Frames are analysed in memory and discarded. |
| **Notifications** | To tell you when an unlock window is about to end. | Nowhere. Notifications are scheduled locally by the app. |
| **Your balance, streak and habit history** | To show what you have earned. | Stored only on your device, in the app's own container and app group. |

> Step counting uses the iOS **Motion & Fitness** permission, and only to read
> today's step total. You can withdraw it at any time in **Settings → Privacy &
> Security → Motion & Fitness**; every other habit keeps working without it.

## What Digital Detox sends about how the app is used

Digital Detox uses **Aptabase**, a privacy-focused analytics service, to
understand how people move through the app — how many get past onboarding, how
many reach the purchase screen, whether restoring a purchase worked. This is the
only thing Digital Detox sends anywhere, and it exists so the app can be
improved without guessing.

**Digital Detox puts no identifier in the events.** No account, no device id, no
IDFA, no advertising identifier, no cookie, and nothing written to your device
that would let two sessions be recognised as the same person.

Aptabase does count unique users, and it is worth being exact about how, because
"anonymous" is a word that gets stretched. Their server derives a temporary id
by hashing your IP address together with the request's user agent and a salt
that they rotate every 24 hours. That id lets them tell one visitor from another
*within a single day*; once the salt rotates, the link is broken and yesterday's
events cannot be joined to today's. The raw IP address is not kept. We never see
any of this — we see counts and charts. Their description of it is here:
<https://aptabase.com/legal/privacy>.

### The events

| Event | What it records |
|---|---|
| App launched | That the app opened. |
| Onboarding shown / onboarding continued | Whether the first screen was passed. |
| Permission result | Which of two permissions was asked for (Screen Time or notifications) and whether it was granted. Never what you blocked. |
| Offer shown / free trial chosen | Which way the post-onboarding offer screen was answered. |
| Price shown | The price and currency code of the one-time unlock, as shown by the App Store in your region, and which screen showed it (the offer or the purchase screen). |
| Paywall shown | That the purchase screen appeared, and whether it appeared because you tapped it or because the trial had ended. |
| Purchase | Whether it succeeded, was cancelled, is pending, was unavailable, or failed — and which screen it was made from. Never any payment detail, and never an error message from the system. |
| Restore | Whether a purchase was restored, there was nothing to restore, or it failed — and which screen it was started from. |
| Habit completed | Which habit type was finished (push-ups, squats, jumping jacks, walking or focus) and how many minutes it earned. |
| Unlock purchased | How many minutes were spent to open your apps. |
| Access lapsed | That a trial ran out without a purchase. |

### What travels with each event

Nothing here is chosen by us; it is what the Aptabase SDK attaches as standard.

| Field | Example | Note |
|---|---|---|
| Timestamp | `2026-09-26T13:47:02Z` | |
| Session id | `178868270012345678` | Generated in memory from the clock plus a random number. It is **not** stored on disk, so it does not survive quitting the app, and it resets after an hour of inactivity. It cannot be linked back to you or to any earlier session. |
| App version and build | `2.0.1 (17)` | |
| Operating system | `iOS 26.3.1` | The system name and version. |
| Device model | `iPhone17,1` | The hardware model only, e.g. "iPhone 16 Pro". Not a serial number and not unique to your device. |
| Language | `en` | The two-letter language code, not your country or region. |
| Debug flag | `false` | Marks events from development builds so they can be discarded. |
| SDK version | `aptabase-swift@0.3.11` | Which version of the analytics library sent the event. |

The operating system name and version and the language code are also sent in
the request's user-agent header, which is the user agent referred to above.

Events are sent to Aptabase's **United States** region. Aptabase acts as a data
processor for Digital Detox and does not sell data or use it for advertising.

Digital Detox's privacy manifest declares exactly one collected data type,
**Product Interaction**, marked as *not linked to identity* and *not used for
tracking* — which is what Apple checks the app against at submission, and
matches the App Store privacy label.

## What else leaves your device

Beyond the analytics above, two things — and neither one goes to us:

1. **A single trial-start timestamp**, mirrored into *your own* iCloud via
   Apple's key-value storage. This is what stops the 7-day free trial from
   resetting when the app is deleted and reinstalled. It is one date and nothing
   else. It syncs between your own devices under your Apple Account; we have no
   access to it.
2. **Your purchase**, handled entirely by Apple's App Store. Digital Detox asks
   StoreKit whether the one-time unlock has been bought. We never see your
   payment details, and Apple's handling of the transaction is covered by
   Apple's own privacy policy.

Digital Detox makes no other network requests.

## Tracking and advertising

> Digital Detox does not track you across apps or websites, shows no
> advertising, and contains no advertising frameworks. The analytics described
> above are not used for advertising, are not shared with data brokers, and are
> not linked to your identity.

Digital Detox does not ask for App Tracking Transparency permission, because it
does not do anything that requires it.

## Children

Digital Detox is rated 4+. It collects no personal information from anyone,
including children: there is no account, no contact detail and no identifier,
so nothing recorded can be traced to a child or to anyone else. The anonymous
usage events described above are collected from all users, are not used for
advertising or profiling, and cannot be used to contact or identify a person.

## Your rights

Where laws such as the GDPR or the CCPA apply, they give you rights over
*personal data* — information that identifies you or could be linked to you.

Digital Detox's analytics carry nothing that identifies you, and the temporary
id described above is a hash we never see, cannot reverse, and which stops
being meaningful within a day. So there is no record anywhere that can be
looked up, exported, corrected or deleted *as yours*.

This is a genuine limitation and worth stating plainly rather than dressing up:
we cannot fulfil an access or deletion request for analytics data, not because
we decline to, but because nothing in the data says which events were yours.
Everything that *is* identifiably yours lives on your device, where you control
it directly. The analytics are part of how the app works and there is no
in-app setting to switch them off; what is sent is limited to the events and
fields listed above, none of which identify you. Deleting the app stops any
further events from being sent.

## Deleting your data

Everything Digital Detox stores about you lives on your device, so deleting the
app removes it. Two things deliberately survive a delete, and how to clear each:

- **The trial-start timestamp in iCloud.** Deleting the app does not remove it,
  by design. To clear it, turn off iCloud for Digital Detox, or remove Digital
  Detox's data in **Settings → [your name] → iCloud → Manage Account Storage**.
- **Screen Time authorisation.** iOS keeps this at the system level. Revoke it
  in **Settings → Screen Time**.

Analytics events already sent cannot be deleted individually, for the reason
given under **Your rights**.

## Changes to this policy

If this policy changes, the "last updated" date above changes with it.

**26 September 2026** — Updated for version 2.0.1. The app is now called
Digital Detox. Step counting now reads today's total from your iPhone's motion
coprocessor through the Motion & Fitness permission, on the device.
Analytics are always on and there is no in-app switch for them; the event list and the fields sent with each event
were brought up to date.

**6 September 2026** — Anonymous usage analytics (Aptabase) were added, and this
policy was rewritten to describe them. Earlier versions of the app made no
network requests at all and collected nothing; if you are running one of those,
the analytics section does not apply to you.

## Contact

Questions about privacy: **dhruwangjariwala18@gmail.com**
