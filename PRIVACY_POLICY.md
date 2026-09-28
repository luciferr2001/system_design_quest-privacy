# Privacy Policy for System Design Quest

_Last updated: 2026-09-28_

This privacy policy explains what data System Design Quest ("the App") collects
and how it is used. The App is developed as a hobby/independent project.

## Summary

System Design Quest lets you sign in with a Google account or as an anonymous
guest so your learning progress (XP, level, streak, completed missions) can
follow you across devices. Your profile and progress are stored in the App's
cloud database (Google Firebase / Cloud Firestore), not just on your device.
The App also shows ads through Google AdMob.

## Account data

When you sign in with **Google**, the App stores:

- Your display name, email address, and profile photo URL, as provided by
  Google Sign-In
- A unique account identifier used to link your progress to your account

When you sign in as a **guest** (no Google account), the App creates a
temporary anonymous account and stores the same profile fields except email
and photo (which are left blank). Guest accounts are tied to the device/app
install that created them - reinstalling the App or clearing its data means
guest progress cannot be recovered, since there is no way to sign back into
that same anonymous account.

## Learning progress data

Whether signed in with Google or as a guest, the App stores in its cloud
database:

- Onboarding answers: your stated role (e.g. "software engineer"), experience
  level, learning goals, and preferred daily study time
- XP, level, current streak, and which missions you have completed
- Individual mission run details (which components you placed, requirement
  results, and score) for missions you complete

This data is used only to run the App's own features (showing your progress,
resuming missions, leaderboards if introduced later) and is not sold or
shared with third parties, other than the service providers below who
process it on the developer's behalf.

## Account deletion

You can sign out of the App at any time. **A self-service "delete my
account" option inside the App is not yet available.** To request deletion
of your account and associated data, contact the developer at the email
address below with the email address or account you signed in with; the
developer will delete the corresponding Firebase Authentication account and
Firestore data.

## Data collected by third-party advertising (Google AdMob)

The App shows ads (banner and rewarded ads) through Google's AdMob SDK
(`google_mobile_ads`) to support free development. AdMob may collect and
process:

- Advertising identifiers (such as your Android Advertising ID)
- Device information (device model, OS version, language, general region)
- App usage and interaction data related to ads shown (impressions, clicks,
  ad performance)
- IP address (used transiently for ad delivery and general location, such as
  country/region)

This data is collected and processed by Google in accordance with Google's
own privacy policy and AdMob's data use policies, not by the developer
directly:

- Google Privacy Policy: https://policies.google.com/privacy
- How Google uses data from apps that use AdMob:
  https://policies.google.com/technologies/partner-sites

You can opt out of personalized advertising, or reset/limit your advertising
identifier, through your device's OS-level ad settings (Settings > Google >
Ads, on most Android devices). Rewarded ads are always optional - you choose
whether to watch one in exchange for an in-app reward.

## Service providers

The App relies on the following third-party services to operate, each of
which processes data according to its own privacy policy:

- **Google Firebase** (Authentication, Cloud Firestore) - stores your
  account and progress data. See
  https://firebase.google.com/support/privacy
- **Google AdMob** - serves ads, as described above.
- **Google Sign-In** - used only if you choose to sign in with Google,
  per Google's own privacy policy.

## What we do NOT do

- We do not access your camera, microphone, photos, contacts, or location.
- We do not sell your data.
- We do not show ads based on browsing outside the App beyond what Google's
  AdMob personalization already does (see above), and you can opt out of
  that through your device settings.

## Children's privacy

The App does not knowingly collect personal information from children, and
is not directed at children. The App requires an account (Google or guest)
to track learning progress and has no chat or user-generated content shared
with other users.

## Changes to this policy

This policy may be updated if the App's data practices change (for example,
if new features, analytics, or ad formats are added). Continued use of the
App after an update constitutes acceptance of the revised policy. The
developer will update the "Last updated" date above whenever this document
changes.

## Contact

For privacy questions, or to request account/data deletion, contact the
developer at: rathodrutik05@gmail.com
