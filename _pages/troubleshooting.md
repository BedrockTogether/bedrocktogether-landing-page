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
there — use the [Switch · Friends broadcast
method](/how-to-join-minecraft-server-nintendo-switch/) instead, which does not rely on
the local network.

**Check the app is actually still running.**
The app has to stay running until you have joined. If you locked your phone or switched
away and the system suspended the app, the LAN world disappears. On Android, exclude
BedrockTogether from battery optimisation. On iOS, keep the app in the foreground until
you are in the server.

**On iOS, check the Local Network permission.**
iOS asks once for permission to find devices on your local network. If you tapped
"Don't Allow", nothing will ever show up. Fix it in
**Settings → BedrockTogether → Local Network**.

**On Nintendo Switch, this will never work.**
The Switch does not display LAN games at all. Use the
[Switch · Friends method](/how-to-join-minecraft-server-nintendo-switch/).

## The server appears, but I get kicked out when I join

At this point the app has done its job — the problem is between you and the server.

* **Wrong port.** Most Bedrock servers use `19132`. If the server publishes a different
  port, it must be entered exactly.
* **The server is offline** or is refusing connections. Try it from another device.
* **The server is on a different Minecraft version.** After Mojang ships a new Bedrock
  release, servers and tools need a few days to catch up. If Minecraft on your console
  just updated and the server has not, or the other way round, connections fail until
  both sides match.
* **The server has a whitelist** and your account is not on it.

## I get "Unable to connect to world"

Same list as above. It is the generic Minecraft message for "the transfer target
refused me", so it points at the destination server rather than at the app.

## Broadcast problems (Switch · Friends)

* **"Your Microsoft account doesn't have an Xbox profile."** Open `xbox.com`, sign in
  with that same account, choose a gamertag, then broadcast again.
* **The broadcast account got banned.** Do not reuse it. Sign out and use another
  separate account — this is why the app warns you never to sign in with your main one.
* **"Broadcasting is temporarily unavailable."** A server-side outage on our end. Try
  again later.
* **The game does not show in the Friends tab.** The broadcasting gamertag has to be a
  friend of the account you play on. Add it from your console first.

## Ads and the paid version

* **Too many ads while troubleshooting.** The ad-free version removes them —
  **Info → Ad-free Version** in the app.
* **"You need premium to save more than 2 servers."** Saving more than two favourite
  servers is a paid feature.

## Still stuck?

Join the [Discord]({{ site.discord_link }}) or email
[{{ site.email_address }}](mailto:{{ site.email_address }}). Please include your
console, your phone's OS, and which of the two methods you were using — it saves a
round trip.

See also: [Xbox guide](/how-to-join-minecraft-server-xbox/) ·
[PlayStation guide](/how-to-join-minecraft-server-playstation/) ·
[Switch guide](/how-to-join-minecraft-server-nintendo-switch/) · [FAQ](/faq/)
