# Toll — Support

Toll locks the apps you choose until you earn screen time back with real effort:
push-ups, squats, jumping jacks, walking or focused work.

**Requires iOS 18 or later, on iPhone.**

## Get help

Email **[your support email]**. Include your iOS version and what you were doing
when it went wrong — that is usually enough to identify the problem on the first
reply.

## Common problems

### My apps are not being blocked

Toll blocks apps through Screen Time, and iOS will let the app run without that
permission — silently, with nothing blocked.

1. Open Toll. If a banner says **"Screen Time access is off"**, tap it and grant
   access.
2. Otherwise check **Settings → Screen Time** is on and has not been turned off
   by a device management profile or a parent/guardian account.
3. Confirm you have actually picked apps: tap **Choose which apps to lock** on
   the home screen. Toll cannot pick for you — iOS never tells the app which apps
   exist, so the selection has to be yours.

### Walking is not earning me anything

Walking is credited from Health's step total, so Toll needs read access to steps.

1. **Settings → Health → Data Access & Devices → Toll → Steps** must be on.
2. If the walk card says Toll cannot see your steps, tap **Open Health** on the
   card and allow it there.
3. Walking pays per whole 1,000 steps. Anything under that is banked and shown as
   "N steps to your next +10 min" — it is not lost.

Toll only ever *reads* steps, and never writes to Health.

### The camera is not counting my reps

Reps are counted by on-device pose detection, which needs to see you.

1. Follow the placement screen: phone upright against a wall, screen facing you.
2. For push-ups, get about 2 feet away with head and shoulders in frame. For
   squats and jumping jacks, step back until your whole body fits.
3. Even, front-on light helps. Backlighting — a bright window behind you — is the
   usual cause of missed reps.
4. Check **Settings → Toll → Camera** is allowed.

No video is recorded or uploaded. Frames are analysed and discarded.

### My apps locked again before the time was up

Two things can cause this:

- **You locked them early.** Tapping *Lock my apps now* returns the unused
  minutes to your balance on purpose.
- **iOS re-locked slightly late or early.** The system's usage accounting is not
  instant and can be off by up to about a minute. This is why the shortest
  purchasable unlock is 15 minutes — at shorter windows the error would be a
  large share of the window.

### The minimum unlock is 15 minutes — can it be shorter?

No. iOS refuses to schedule the underlying monitoring window below 15 minutes,
and shorter unlocks could not be delivered accurately.

### I hit a daily cap

The balance is capped at 240 minutes so a day's earnings cannot be banked
indefinitely and defeat the point. When you are at the cap, spend some before
earning more.

### I paid, but Toll is asking me to buy again

Tap **Restore purchase** on the paywall. This asks the App Store to re-sync your
purchases. Make sure you are signed into the same Apple Account you bought with.
Toll is a single one-time purchase, not a subscription — there is nothing to
renew and nothing to cancel.

### My free trial ended sooner than I expected

The trial is 7 days from first launch, and its start date is stored in your
iCloud so it survives deleting and reinstalling the app. Reinstalling does not
give you a fresh 7 days.

### Can I change the language?

Yes — tap the **globe** row at the bottom of the home screen. Toll ships in 16
languages and this setting is independent of your phone's language.

### How do I stop using Toll entirely?

Open Toll and clear your app selection, or revoke access in **Settings → Screen
Time**, then delete the app. Deleting the app alone does not revoke Screen Time
authorisation, because iOS keeps that at the system level.

## Privacy

Toll has no account, no analytics and no server. See the
[Privacy Policy](privacy-policy.md).

## Feature requests and bugs

Email the address above. Bug reports that name the exact screen and the exact
step that failed get fixed fastest.

<!-- Fill in the support address above before publishing. Apple requires a
     working contact on the page a Support URL points at. -->
