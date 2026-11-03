---
layout: page
title: BedrockTogether FAQ
nav_title: FAQ
nav_order: 5
include_in_header: true
description: "Is BedrockTogether free? Is it safe? Does it work on Nintendo Switch? Do I need a PC? Answers to the questions we get asked most."
seo:
  type: WebPage
---

# Frequently Asked Questions

## Is BedrockTogether free?

Yes. The app is free on the App Store and Google Play, and is paid
for by ads. **BedrockTogether Pro** is a one-time payment, with no subscription: it
removes ads, lets you save unlimited favourite servers (the free app allows 2) and
hides the Partnered Servers list. On Android, Pro is a separate app on
[Google Play]({{ site.playstore_pro_link }}); on iOS it is an in-app purchase under
**Info → Ad-free Version**. In Pro the button reads "Run" instead of "Watch Ad and Run".

## Do I need a PC?

No. Everything runs on your phone. Older ways of getting console Minecraft onto a custom
server needed a computer running a proxy, or a change to your console's DNS settings.
BedrockTogether needs neither.

## Do I need to change my console's DNS settings?

No, and you should undo them if an older guide had you set them. BedrockTogether does not
use DNS.

## Which consoles does it work on?

Xbox One, Xbox Series S and Series X, PlayStation 4 and PlayStation 5 all work with the
LAN method. Nintendo Switch needs the
[Friends broadcast](/how-to-join-minecraft-server-nintendo-switch/) instead, because the
Switch does not display LAN games. That broadcast is **Android only**; on iPhone and
iPad it is not available. It also works on mobile and PC editions.
<!-- TODO owner: Switch on iOS / Alternative -->

## Which Minecraft and phone versions are supported?

Minecraft **1.26.60 and newer**. Your phone needs Android 8.0 or newer, or iOS 15 or
newer.

## Why doesn't the normal method work on Nintendo Switch?

Minecraft on Switch does not list LAN games at all, so there is nothing for the app to
appear in. The **Friends** broadcast method (Android app) goes through Xbox Live instead.
Read the account warning on that page before you use it.

## Will I get banned for using this?

Two different answers, depending on the method.

**The LAN method** (Xbox, PlayStation) uses Minecraft's ordinary local-network
discovery — the same thing that happens when someone in your house opens a world to LAN.

**The broadcast method** (the Friends tab, Android) works by emulating a game client against
Xbox Live. This may break Xbox Live's terms of service, and the account you sign in with
could be banned. Always sign in with a **separate, throwaway Microsoft account**, never
the one you play on. The app warns you about this before sign-in, and we mean it.

## Do the phone and the console need to be on the same Wi-Fi?

For the LAN method, yes — that is the whole mechanism. For the broadcast method, no.

## Do I have to leave the app open the whole time I play?

No. Keep it running until you have joined the server. Once you are in and playing, the
app has finished its work and you can close it.

## What port should I use?

`19132` unless the server tells you otherwise. That is the default for Minecraft Bedrock
servers. That is the port of the *server* you join. Separately, the phone uses UDP port
`7551` to show the LAN world to your console; if the app says that port is in use, fully
close Minecraft on that device and any other server apps, then start again.

## Where do I find servers to play on?

Any public Bedrock server address works. On Android the **Servers** tab is a searchable
catalog, with sponsored and partner rows marked, and live player counts that are
measured from your own device — "Offline" means your device could not reach that server.
The app also lists Partnered Servers on the main screen (Pro hides that list), and you
can save your own favourites (2 in the free app, unlimited in Pro).

## Can I use my own server?

Yes. Enter its address and port like any other. If you want a server that stays online
around the clock, the app has a partner offer under **Create your own server**.

## Is this an official Minecraft app?

No. BedrockTogether is not affiliated with or endorsed by Microsoft, Mojang, Xbox, Sony
or Nintendo.

## It isn't working. What now?

Work through the [troubleshooting page](/troubleshooting/) — it covers essentially every
report we receive. If you are still stuck, the [Discord]({{ site.discord_link }}) is the
fastest way to reach us.

See also: [Xbox guide](/how-to-join-minecraft-server-xbox/) ·
[PlayStation guide](/how-to-join-minecraft-server-playstation/) ·
[Switch guide](/how-to-join-minecraft-server-nintendo-switch/) ·
[Troubleshooting](/troubleshooting/)

<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "Is BedrockTogether free?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes. The app is free on the App Store and Google Play and is paid for by ads. BedrockTogether Pro is a one-time payment that removes ads, allows unlimited favourite servers and hides the Partnered Servers list. On Android it is a separate app on Google Play; on iOS it is an in-app purchase."
      }
    },
    {
      "@type": "Question",
      "name": "Do I need a PC to join a Minecraft server on console?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "No. Everything runs on your phone. BedrockTogether needs neither a computer running a proxy nor a change to your console's DNS settings."
      }
    },
    {
      "@type": "Question",
      "name": "Which consoles does BedrockTogether work on?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Xbox One, Xbox Series S and Series X, PlayStation 4 and PlayStation 5 work with the LAN method. Nintendo Switch needs the Xbox Live Friends broadcast instead, because the Switch does not display LAN games. The Friends broadcast is available on Android only; on iPhone and iPad it is not available. Minecraft 1.26.60 or newer is required."
      }
    },
    {
      "@type": "Question",
      "name": "Why doesn't the LAN method work on Nintendo Switch?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Minecraft on Nintendo Switch does not list LAN games at all, so there is nothing for the app to appear in. The Friends broadcast method (Android app) goes through Xbox Live instead."
      }
    },
    {
      "@type": "Question",
      "name": "Will I get banned for using BedrockTogether?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The LAN method used on Xbox and PlayStation relies on Minecraft's ordinary local-network discovery. The Friends broadcast method (Android) emulates a game client against Xbox Live, which may break Xbox Live's terms of service, and the account signed in could be banned. Always use a separate throwaway Microsoft account for broadcasting, never your main one."
      }
    },
    {
      "@type": "Question",
      "name": "Do the phone and the console need to be on the same Wi-Fi network?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "For the LAN method, yes — that is the whole mechanism. For the Xbox Live broadcast method, no."
      }
    },
    {
      "@type": "Question",
      "name": "Which Minecraft version does BedrockTogether support?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Minecraft 1.26.60 and newer. The phone needs Android 8.0 or newer, or iOS 15 or newer."
      }
    },
    {
      "@type": "Question",
      "name": "Do I have to leave the app open while I play?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Only until you have joined the server. Once you are in and playing you can close the app."
      }
    },
    {
      "@type": "Question",
      "name": "What port do Minecraft Bedrock servers use?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Port 19132 is the default for Minecraft Bedrock servers. Use that unless the server publishes a different one."
      }
    },
    {
      "@type": "Question",
      "name": "Is BedrockTogether an official Minecraft app?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "No. BedrockTogether is not affiliated with or endorsed by Microsoft, Mojang, Xbox, Sony or Nintendo."
      }
    }
  ]
}
</script>
