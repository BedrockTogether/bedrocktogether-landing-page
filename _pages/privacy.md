---
layout: page
title: BedrockTogether Privacy Policy
nav_title: Privacy
nav_order: 7
include_in_header: false
description: "How BedrockTogether handles your data: what is collected, who it is shared with, how age assurance works, and how to exercise your rights."
seo:
  type: WebPage
---

# Privacy Policy

**Last updated: 3 November 2026**

This policy explains what BedrockTogether collects, why, and what you can do about
it. It covers the BedrockTogether and BedrockTogether (Pro) apps on the App Store
and Google Play.

BedrockTogether is not affiliated with or endorsed by Microsoft, Mojang, Xbox,
Sony or Nintendo.

## Who is responsible

BedrockTogether is operated by **Jędrzej Racibor**, based in Poland. For anything
in this policy, including requests about your data, contact
[jedrzej@extollite.pl](mailto:jedrzej@extollite.pl).

Because the operator is established in the European Union, the GDPR applies
directly to this app worldwide, alongside local rules in the country you use it
from.

## What stays on your device

Your saved favourite servers and your app settings are stored **on your device
only**. They are not uploaded, and they are removed when you uninstall the app.

The server addresses and ports you enter are **not** purely local: when you start a
transfer or a broadcast, the address and port you used are sent to our service, as
described under "Connection events" below. The address is also sent to that server
when you connect to it, because that is how connecting works. We are not a party to
that connection.

**Live player counts.** To show whether a listed server is online and how many
players it has, your device contacts the servers visible in the app's server lists
directly. Those servers, which are run by third parties, can see your IP address
when this happens, even if you do not join them. We do not receive the results.
These checks do not go through our service.

## What the app collects

**A per-install identifier.** The app generates a random identifier the first time
it runs and keeps it until you uninstall. It is sent with each connection event to
our own service (below) and is set as the user ID on crash reports, so that repeated
events from one device can be counted once rather than many times. It is not your
name, your account, or an identifier that follows you across other apps, but it is
stable for as long as the app stays installed. The app does not currently display
this identifier anywhere. (Firebase Analytics also keeps its own app-instance
identifier, which is separate.)

**Connection events.** Each time you start a transfer or a broadcast, the app sends
a record to our own service at `extollite.pl`. That record contains the **server
address and port** you transferred to (or, for a broadcast, the target host), the
**per-install identifier**, and the **device type** (iOS or Android). Our service adds
the time it received it. The record is therefore linked to your install: the history
of servers connected to from one install can be put together. It is pseudonymous,
because it holds no name, account or email, but it is not anonymous. Our service does
not store your IP address with the record. Separately, the same action is sent to
Firebase Analytics as an event naming the method used (and, if you pick a listed or
partnered server, that server), and failures are sent with a short reason category.
If you use Pro, the same applies in that app.

**Crash and performance diagnostics,** through Firebase Crashlytics, so faults can
be found and fixed. Crash reports carry the per-install identifier as the user ID.

**Servers that help your devices connect.** To let a console reach your phone, the
app asks our Cloudflare-hosted service for relay (TURN/ICE) server details, and a
signaling service passes the connection setup between the devices. Those requests
reveal your IP address to Cloudflare as the network provider, and the signaling
service sees the host and port of the destination server involved and records it in
operational logs. Requests may also carry the app's name and version, and, where
supported, an app-integrity token from Firebase App Check (Google Play Integrity or
Apple App Attest), used to check the request comes from a genuine copy of the app.
When a relay is used, your game traffic for that session passes through Cloudflare's
relay. We do not store a profile from these requests. The app may also ask a public
STUN server run by Cloudflare for your public address, to set up the connection.

**Diagnostic logs.** If you switch on diagnostic logging in the app, technical
connection logs are kept on your device (for seven days on iOS) and are only
shared if you choose to share them. Nothing is uploaded automatically.

**Advertising identifiers and ad interaction data,** handled by the advertising
partners listed below. Those partners may also derive an approximate location
(typically city-level, from your IP address). The app itself never asks for or
uses precise location — there is no location permission in the app.

**Xbox Live sign-in (only if you use Switch · Friends).** If you use the broadcast
feature, you sign in with a Microsoft account. The resulting token is stored
encrypted on your device and used to publish the session. We do not receive your
Microsoft password. We strongly recommend using a separate account for this, as
the app warns before sign-in.

## Age assurance

To keep the app appropriate for younger players and to meet children's privacy
law, the app needs a rough idea of how old you are.

**Where the age comes from.** On supported devices, the app asks the operating
system for an age *range* — Apple's Declared Age Range on iOS, Google's Play Age
Signals on Android. You or a parent control whether that range is shared, and it
is a band such as "13–15" or "18+", never a date of birth. Where the platform
cannot answer, the app asks you directly for your month and year of birth.

**What is stored.** Only the resulting band — child, below the local threshold, or
at/above it. **Your date of birth is not stored**, not sent anywhere, and not
attached to any analytics event.

**What it changes.** Below the applicable age for your country, personalised
advertising and tracking are switched off: no advertising identifier is
transmitted, and ads are selected from context rather than from anything about
you. The threshold varies by country because the law does — 13 in the United
States, 13 to 16 across the EU, 18 in the United Kingdom and India.

The age result is used only to apply these protections. It is never used to target
advertising, to build a profile, or for analytics.

## Advertising

The free app is paid for by advertising. Depending on your region, ads may be
served or mediated by:

* [Google AdMob](https://policies.google.com/privacy)
* [Meta Audience Network](https://www.facebook.com/about/privacy)
* [Unity Ads](https://unity.com/legal/game-player-and-app-user-privacy-policy)
* [Liftoff Monetize (Vungle)](https://vungle.com/privacy/)
* [Pangle](https://www.pangleglobal.com/privacy) — used in Russia and Belarus,
  where the networks above do not serve

These partners are independent controllers of the data they collect. Their own
policies, linked above, govern what they do with it.

**Ad-free option.** The Pro app and the in-app ad-free purchase remove advertising
entirely, and with it the advertising SDKs' collection.

## Your choices

**Consent (EEA and UK).** On first launch you are asked, through Google's
certified consent platform, whether you agree to personalised advertising. You can
change that answer at any time from the privacy options in the app.

**App Tracking Transparency (iOS).** iOS asks separately whether the app may track
you. Declining does not affect any feature — you will simply see less relevant
ads. You can change it in **Settings → Privacy & Security → Tracking**.

**Reset your advertising identifier** at any time in your device settings, which
disconnects past ad activity from future activity.

**Your GDPR rights.** You can ask for access to, correction of, or erasure of your
data; object to processing; or withdraw consent. Email
[jedrzej@extollite.pl](mailto:jedrzej@extollite.pl) and include the approximate date
you first used the app so the request can be matched. Requests are answered within
one month. You also have the right to complain to your data protection authority —
in Poland, the President of the Personal Data Protection Office (UODO).

**Deleting everything.** Uninstalling the app removes all locally stored data,
including the per-install identifier. It does **not** remove connection records
already stored on our server (see "How long data is kept"). Because the identifier
is not shown in the app, tell us which app, the approximate dates you used it and
servers you connected to when you email the address above; we will try to find
and delete the records that match. Deletion of records by identifier is technically
possible. We can only find records we can match, so a request that gives too little
information may not be fulfilled, and we will tell you if so.

## Legal bases (GDPR)

* **Consent** — personalised advertising, and analytics where consent is required.
* **Legitimate interests** — keeping the app working, diagnosing crashes,
  preventing abuse, counting usage, and keeping a record of connections made
  through the app.
* **Legal obligation** — age assurance and the protections that follow from it.
* **Contract** — providing the connection features you asked for.

## Children

BedrockTogether is a utility for Minecraft players, and we know some of them are
children.

We do not knowingly collect personal information from a child below the applicable
age in their country for advertising purposes. Where the age assurance described
above identifies a user as below that age, personalised advertising and tracking
are disabled and no advertising identifier is transmitted.

If you are a parent or guardian and believe your child has provided personal
information, email [jedrzej@extollite.pl](mailto:jedrzej@extollite.pl) and it will be
deleted.

## How long data is kept

Locally stored data lasts until you uninstall.

**Connection records on our server are kept indefinitely.** For roughly the first
365 days they sit in a Cloudflare D1 database. After that, a daily job moves them
into Cloudflare R2 object storage as compressed archive files. Nothing is deleted
automatically, either from the database or from the archive. Older records from our
previous self-hosted server (a VPS running PostgreSQL) are being archived the same way,
and that server is being retired. You can ask for records to be deleted at any time,
as described above.

Crash reports and Firebase Analytics data are kept according to the retention
settings of Firebase (Google). Advertising partners apply their own retention
periods, described in their policies.

## Where data is processed

Our service runs on Cloudflare (Workers, D1 database and R2 storage), which acts as
our hosting provider and processor. In the normal course of serving any request,
Cloudflare as a network provider sees the IP address of whoever makes it; our service
does not store that address with connection records. Firebase (Google) processes
analytics and crash data. Data may be processed outside your country, including
outside the EEA.

## Changes to this policy

This policy will be updated when the app changes. The date at the top always shows
the current version. Material changes will be announced in the app.

---

*This policy describes how the app actually behaves and is written to be
understood, not to be exhaustive legal drafting. If something here is unclear or
looks wrong, please write and it will be corrected.*
