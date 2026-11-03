---
layout: page
title: BedrockTogether Troubleshooting
nav_title: Troubleshooting
nav_order: 4
include_in_header: true
description: "Server not showing up in Minecraft? Kicked out on join? Fixes for the most common BedrockTogether problems on Xbox, PlayStation and Nintendo Switch."
seo:
  type: WebPage
---

# Troubleshooting

Start here before contacting support — almost every report we get is one of the
following.

## The server does not show up in the Worlds tab

This is the most common problem, and it is almost always the network rather than the
app.

**Check the phone and the console are really on the same network.**
Not just "both on Wi-Fi at home". Many routers broadcast a main network and a **guest
network** under different names, and devices on the guest network cannot see each other.
Check the exact network name on both devices. If your phone is on mobile data, or on a
VPN, the console will not see it either — turn the VPN off.

**Check your router is not isolating clients.**
Look in your router settings for *AP isolation*, *client isolation*, *Wireless
isolation* or *Guest mode* and turn it off for the network both devices use. This is on
by default on a lot of hotel, dorm and campus Wi-Fi, and you usually cannot change it
there — on Android, use the [Friends broadcast
method](/how-to-join-minecraft-server-nintendo-switch/) instead, which does not rely on
the local network.

**Check the app is actually still running.**
The app has to stay running until you have joined. If you locked your phone or switched
away and the system suspended the app, the LAN world disappears. On Android, allow
BedrockTogether to show notifications (**Settings → Apps → BedrockTogether →
Notifications**) — the app keeps itself running through a foreground-service
notification, and Android can stop it if notifications are blocked. On iOS, keep the app
in the foreground until you are in the server.

**Check "Visible to LAN Players" in Minecraft.**
In Minecraft's multiplayer settings, make sure **Visible to LAN Players** is turned ON.

**On iOS, check the Local Network permission.**
iOS asks once for permission to find devices on your local network. If you tapped
"Don't Allow", nothing will ever show up. Fix it in
**Settings → BedrockTogether → Local Network**.

**On Nintendo Switch, this will never work.**
The Switch does not display LAN games at all. On Android, use the
[Friends method](/how-to-join-minecraft-server-nintendo-switch/). On iPhone and iPad
the Friends broadcast is not available.
<!-- TODO owner: Switch on iOS / Alternative -->

**The app says the port is already in use.**
The LAN world is advertised from your phone on UDP port `7551`, and only one app can
use it at a time. Fully close Minecraft on that device and any other server apps, then
start BedrockTogether again.

**Check your Minecraft version.**
BedrockTogether supports Minecraft **1.26.60 and newer**. Update Minecraft on your
console if it is older.

## The server appears, but I get kicked out when I join

At this point the app has done its job — the problem is between you and the server.

* **Wrong port.** Most Bedrock servers use `19132`. If the server publishes a different
  port, it must be entered exactly.
* **The server is offline** or is refusing connections. Try it from another device.
* **Your Minecraft is too old.** BedrockTogether supports Minecraft **1.26.60 and
  newer**. Update Minecraft on your console.
* **The server is on a different Minecraft version.** After Mojang ships a new Bedrock
  release, servers need a few days to catch up. If Minecraft on your console just
  updated and the server has not, or the other way round, connections fail until both
  sides match.
* **The server has a whitelist** and your account is not on it.

## I get "Unable to connect to world"

Same list as above. It is the generic Minecraft message for "the transfer target
refused me", so it points at the destination server rather than at the app. The app's
own help also suggests:

* Set your skin to Alex or Steve.
* PlayStation: go to your console **Settings → Account management → Restore Licenses**.
* Restart Minecraft, restart your router, or log in with a different Microsoft account.

## "Sorry, we couldn't validate your login"

Restart Minecraft, or log in to a different Microsoft account.

## Minecraft keeps "locating server"

Try a different server.

## Broadcast problems (Friends tab, Android)

The Xbox Live Friends broadcast is **Android only**. On iPhone and iPad it is not
available.
<!-- TODO owner: Switch on iOS / Alternative -->


* **"Your Microsoft account doesn't have an Xbox profile."** Open `xbox.com`, sign in
  with that same account, choose a gamertag, then broadcast again.
* **The broadcast account got banned.** Do not reuse it. Sign out and use another
  separate account — this is why the app warns you never to sign in with your main one.
* **"Broadcasting is temporarily unavailable."** A server-side outage on our end. Try
  again later.
* **The game does not show in the Friends tab.** The broadcasting gamertag has to be a
  friend of the account you play on. Add it from your console first. While the
  broadcast is running, the app accepts friend requests automatically (about every 20
  seconds), so allow a moment after sending one.
* **A message about a guardian, an unfinished account step, your region, or too many
  devices.** The app shows the reason: a guardian must allow online play at
  `account.microsoft.com/family`; finish any pending step at `account.microsoft.com`;
  Xbox Live may not be available in your country; or sign out on another device.
* **"Your sign-in expired."** Sign out and sign in again.

## Ads and the paid version

* **Too many ads while troubleshooting.** BedrockTogether Pro removes them. On Android
  Pro is a separate app on [Google Play]({{ site.playstore_pro_link }}); on iOS it is an
  in-app purchase under **Info → Ad-free Version**. It is a one-time payment, with no
  subscription.
* **"You need premium to save more than 2 servers."** Pro lets you save unlimited
  favourite servers. Pro also hides the Partnered Servers list.

## Diagnostics report

If support asks for a log: open **Info → Diagnostics** (on Android, **Info → Settings → Diagnostics**), turn on **Enable diagnostic
logging**, try joining once, then use **Share diagnostic report**. Reports leave out
credentials, player names and network addresses, are kept on your device for at most 7
days, and nothing is uploaded automatically — you choose whether and where to send it.
Turn logging off again when you are done.

## Requirements

* Android 8.0 or newer, or iOS 15 or newer
* Minecraft 1.26.60 or newer

## Still stuck?

Join the [Discord]({{ site.discord_link }}) or email
[{{ site.email_address }}](mailto:{{ site.email_address }}). Please include your
console, your phone's OS, and which method (LAN or Friends) you were using — it saves a
round trip.

See also: [Xbox guide](/how-to-join-minecraft-server-xbox/) ·
[PlayStation guide](/how-to-join-minecraft-server-playstation/) ·
[Switch guide](/how-to-join-minecraft-server-nintendo-switch/) · [FAQ](/faq/)
