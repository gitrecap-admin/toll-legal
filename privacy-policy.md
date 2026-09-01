# Privacy Policy — Toll

**Last updated: 1 September 2026**

Toll is an iOS app that locks the apps you choose until you earn screen time back
with push-ups, squats, jumping jacks, walking or focused work.

## The short version

Toll has no account, no analytics, no advertising, no third-party SDKs and no
server of its own. We do not collect, receive, store or sell any information
about you. Nothing you do in Toll is visible to us, because there is nowhere for
it to be sent.

## What Toll collects about you

Nothing.

There is no sign-up, no email address, no device identifier and no usage
reporting. Toll's privacy manifest declares no collected data types and no
tracking domains, which is what Apple checks the app against at submission.

## What Toll accesses on your device

Each of these is used for one purpose, on your device, and never leaves it
except where explicitly stated in the next section.

| What | Why | Where it goes |
|---|---|---|
| **Screen Time (Family Controls)** | To shield the apps you pick and unshield them when you spend earned minutes. | Nowhere. iOS never tells Toll which apps you picked — the app only ever holds opaque tokens with no name or bundle identifier attached. |
| **Health — step count (read only)** | To credit screen time for walking you have already done. | Nowhere. Toll reads today's step total and never writes to Health. |
| **Camera** | To count reps with on-device pose detection. | Nowhere. No video or still image is recorded, saved, or transmitted. Frames are analysed in memory and discarded. |
| **Notifications** | To tell you when an unlock window is about to end. | Nowhere. Notifications are scheduled locally by the app. |
| **Your balance, streak and habit history** | To show what you have earned. | Stored only on your device, in the app's own container and app group. |

Toll requests read-only Health access. It never asks for permission to write to
Health, and cannot.

## What leaves your device

Two things, and neither one goes to us:

1. **A single trial-start timestamp**, mirrored into *your own* iCloud via
   Apple's key-value storage. This is what stops the 7-day free trial from
   resetting when the app is deleted and reinstalled. It is one date and nothing
   else. It syncs between your own devices under your Apple Account; we have no
   access to it.
2. **Your purchase**, handled entirely by Apple's App Store. Toll asks StoreKit
   whether the one-time unlock has been bought. We never see your payment
   details, and Apple's handling of the transaction is covered by Apple's own
   privacy policy.

Toll makes no other network requests.

## Tracking and advertising

Toll does not track you across apps or websites, shows no advertising, and
contains no advertising or analytics frameworks. There is no data to share,
because none is collected.

## Children

Toll is rated 4+ and collects no data from anyone, including children. It
contains no user-generated content, no chat, no web browser and no external
links to third-party content.

## Deleting your data

Everything Toll stores about you lives on your device, so deleting the app
removes it. Two things deliberately survive a delete, and how to clear each:

- **The trial-start timestamp in iCloud.** Deleting the app does not remove it,
  by design. To clear it, turn off iCloud Drive for Toll, or remove Toll's data
  in **Settings → [your name] → iCloud → Manage Account Storage**.
- **Screen Time authorisation.** iOS keeps this at the system level. Revoke it in
  **Settings → Screen Time**, or from inside Toll before deleting.

## Changes to this policy

If this policy changes, the "last updated" date above changes with it. Because
Toll collects nothing, any change would be a clarification rather than a new use
of your data.

## Contact

Questions about privacy: **[your support email]**

<!-- Fill in the address above before publishing. Apple requires a working
     contact on the page a Privacy Policy URL points at. -->
