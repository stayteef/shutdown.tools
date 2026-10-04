
<!--
451

<div class="tool" markdown>

LOGO
![Bridgefy logo](assets/iodine.png){ align=right width=88 }

NAME
### Bridgefy

description
**Bridgefy** is a tool that you can send encrypted messages with other Bridgefy users within 100 meters by Bluetooth without internet. It allows texts, voice notes and locations.

info
**Platforms:** [:simple-android:](https://play.google.com/store/apps/details?id=me.bridgefy.main){ title="Android" } [:simple-apple:](https://apps.apple.com/us/app/bridgefy-offline-messages/id975776347){ title="iOS" }

**Open source:** :material-close:

**Last Updated:** 26 Aug 2026

[:octicons-globe-16: Official website](https://bridgefy.me/){ .md-button }

REVIEWS
<div class="reviews" markdown>
<span class="label">User reviews</span>

"It only works within 100 meters..." — Anonymous, Hong Kong, Sept 2026
</div>

END of template

</div>
-->

<!-- description-->
Using an **e-SIM** allows you to activate a foreign mobile data plan without needing to insert a physical card into your device. It enables you to switch between different mobile networks and access alternative providers that may still be operational, ensuring connectivity even when local networks are restricted.

<!-- info-->
**Platforms:** [:simple-android:](URL){ title="Android" } [:simple-apple:](URL){ title="iOS" }

<!-- RISKS -->
!!! warning "Risks"

    - It may not be a good solution in areas with a complete network outage, or where all provider  s are affected.

<!-- PREPARE -->
!!! warning "Must test first"

    - Get the e-SIM BEFORE a shutdown happens, and test that it actually works on your device and carrier. You need to make sure.

<!-- WARNING/REMINDER-->



<!-- Iodine -->
<div class="tool" markdown>

<!-- LOGO-->
![Iodine logo](assets/iodine.png){ align=right width=88 }

<!-- NAME -->
### Iodine

<!-- description-->
⚠️ **Highly technical. Requires real networking skill to set up. Not beginner-friendly.**

**Iodine** is a tool that can sneak your internet traffic past certain kinds of blocks. During SOME shutdowns, authorities don't switch off the network completely. They leave a few small background channels open, because phones and computers need them just to function. Iodine hides your internet traffic inside one of those still-open channels, letting it slip past the block. The channel it uses is called DNS, the system that looks up website names, which is often left working even when normal internet is cut off.

<!-- info-->
**Platforms:** :material-console:{ title="Command line" } [:simple-linux:](URL){ title="Linux" }  

**Open source:** :material-check:

[:octicons-globe-16: Official website](https://code.kryo.se/iodine/){ .md-button }

!!! info "When it won't help"

    Iodine only works in a limited set of cases, and whether it works depends on a lot of factors, for example, whether DNS is still allowed (which is not easy to check), which DNS provider you're routed through, and your own technical skill. **It does nothing in these cases:**

    - If DNS is blocked in your country.

    - A total blackout, where the network is fully switched off.

    - Physical damage or a power cut that takes the network down entirely.

    - Countries or networks that filter or heavily restrict DNS.

<!-- WARNING/REMINDER-->
- [**Briar**](https://briarproject.org/) 
    - Censorship-resistant peer-to-peer messaging that bypasses centralized servers. Briar allows you to privately connect via Bluetooth, Wi-Fi or Tor. Available on [Android](https://play.google.com/store/apps/details?id=org.briarproject.briar.android), [F-Droid](https://briarproject.org/fdroid). 

- [**Bridgefy**](https://bridgefy.me/) 
    - Bridgefy is a free messaging app that works without the Internet.Available on [Android](https://play.google.com/store/apps/details?id=me.bridgefy.main), [iOS](https://apps.apple.com/us/app/bridgefy-offline-messages/id975776347).

- [**Deku SMS**](https://dekusms.com/)
     - DekuSMS is an Android SMS app that allows you to encrypt your SMS.
     <span style="color:red; font-style:italic;">Authorities will be able to see a large amount of ciphertext being sent from your number, especially when your SIM is registered with your ID.</span>

- [**JAMI**](#) 
    - **Lorem Ipsum**.

- [**Meshtastic**](https://meshtastic.org/)meshtastic.webp
     - Meshtastic is a decentralized wireless off-grid mesh networking LoRa protocol that operates on low-power devices. It enables users to communicate with their app using LoRa technology without an internet connection.
     - <span style="color:red; font-style:italic;">Requires purchasing a physical device.</span>

| Chat App    | Bluetooth | Wi-Fi | LoRa | SMS | Internet | Images/Files Sharing | Open Source | Requires Physical Device |
|-------------|-----------|-------|------|-----|----------|----------------------|-------------|-------------------------|
| Briar       | ✔️         | ✔️     | ❌    | ❌   | ✔️        | ✔️                    | ✔️           | ❌                       |
| Bridgefy    | ✔️         | ✔️     | ❌    | ❌   | ✔️        | ✔️                    | ❌           | ❌                       |
| JAMI        | ✔️         | ✔️     | ❌    | ❌   |         | ✔️                    | ✔️           | ❌                       |
| Deku SMS    | ❌         | ❌     | ❌    | ✔️   | ❌        | ✔️                    | ✔️           | ❌                       |
| Meshtastic  | ✔️         | ✔️     | ✔️    | ❌   | ❌        | ❌                    | ✔️           | ✔️                       |



# Alternative Internet
<!-- e-sim-->
<div class="tool" markdown>

<!-- LOGO-->
![Tool Name logo](assets/toolname.png){ align=right width=88 }

<!-- NAME -->
### e-SIM

<!-- description: one line on what it does and who it's for -->
Using an **e-SIM** allows you to activate a foreign mobile data plan without needing to insert a physical card into your device. It enables you to switch between different mobile networks and access alternative providers that may still be operational, ensuring connectivity even when local networks are restricted. However, it may not be a good solution in areas with complete network outages or where all providers are affected.

<!-- info-->
**Platforms:** [:simple-android:](https://example.com/android){ title="Android" } [:simple-apple:](https://example.com/ios){ title="iOS" } [:material-web:](https://example.com/web){ title="Web" } :material-chip:{ title="Hardware" }  
**Open source:** :material-check: &nbsp;·&nbsp; **Non-profit:** :material-check:  
**Target:** In-country friends / Public posting
**Last Updated:** ?

[:octicons-globe-16: Official website](https://example.com){ .md-button }

<!-- RISKS -->
!!! warning "Risks"

    - It may not be a good solution in areas with a complete network outage, or where all providers are affected.

<!-- PREPARE -->
!!! warning "Must test first"

    - Get the e-SIM **BEFORE** a shutdown happens, and test that it actually works on your device and carrier. You need to make sure.

</div>

<!-- Starlink-->
<div class="tool" markdown>

<!-- LOGO-->
![Tool Name logo](assets/toolname.png){ align=right width=88 }

<!-- NAME -->
### Iodine

⚠️ **Highly technical. Requires real networking skill to set up. Not beginner-friendly.**

**Iodine** is a tool that can sneak your internet traffic past certain kinds of blocks. During SOME shutdowns, authorities don't switch off the network completely. They leave a few small background channels open, because phones and computers need them just to function. Iodine hides your internet traffic inside one of those still-open channels, letting it slip past the block. The channel it uses is called DNS, the system that looks up website names, which is often left working even when normal internet is cut off.

<!-- info-->
**Platforms:** :material-console:{ title="Command line" } [:simple-linux:](URL){ title="Linux" }  
**Open source:** :material-check:

[:octicons-globe-16: Official website](https://code.kryo.se/iodine/){ .md-button }

!!! info "When it won't help"

    Iodine only works in a limited set of cases, and whether it works depends on a lot of factors, for example, whether DNS is still allowed (which is not easy to check), which DNS provider you're routed through, and your own technical skill. **It does nothing in these cases:**

    - If DNS is blocked in your country.

    - A total blackout, where the network is fully switched off.

    - Physical damage or a power cut that takes the network down entirely.

    - Countries or networks that filter or heavily restrict DNS.

<!-- REVIEWS-->
<div class="reviews" markdown>
<span class="label">User reviews</span>

"Need to set up with internet, very complicated" — Anonymous, Kenya, Jan 2026

"Reliable but drains the battery fast." — Adam (facebook developer), Ukraine, Feb 2026
</div>
</div>

<div class="tool" markdown>

<!-- LOGO-->
![Satellite Internet logo](assets/satellite.png){ align=right width=88 }

<!-- NAME -->
### Satellite Internet

<!-- description-->
**Satellite internet** works like normal internet, but it's provided by a company like SpaceX instead of your local ISP, bypassing the local network your authorities control. There are a few providers on the market. The most common is Starlink by SpaceX. It involves a one time hardware kit and a monthly subscription.

<!-- info-->
**Platforms:** :material-chip:{ title="Hardware" }  
**Open source:** :material-close: &nbsp;·&nbsp; **Non-profit:** :material-close:

<!-- provider comparison -->
| Provider   | Speed Range                     | Starting Monthly Cost | Regular Monthly Cost | Contract | Monthly Equipment Costs               | Data Cap                     | Owned By                     |
|------------|----------------------------------|-----------------------|----------------------|----------|---------------------------------------|-------------------------------|------------------------------|
| Hughesnet  | 25-100 Mbps download, 5 Mbps upload | $50-$95               | $75-$120             | 2 years  | $10-$20 a month or $300-$450 one-time purchase | Unlimited, 100-200 GB (soft cap) | [EchoStar](https://www.echostar.com) |
| Starlink   | 100-350 Mbps download, 5-25 Mbps upload | $80-$120              | $80-$120             |          | $349 (currently discounted to $89) one-time purchase for Standard | Unlimited | [SpaceX](https://www.spacex.com) |
| Viasat     | 25-150 Mbps download, 3 Mbps upload | $70-$100              | $70-$100             | None     | $15 or $250 one-time purchase         | Unlimited, 850 GB (soft cap) | [Viasat Inc.](https://www.viasat.com) |

<!-- RISKS -->
!!! warning "Risks"

    - In some countries it is not legal to obtain or use Starlink.

<!-- WARNING/REMINDER-->
!!! danger "Warning"

    Please be aware of the risks of being detected using satellite internet.
    The Iranian community created [a guide on how to mitigate the risks of being detected](https://www.starlink4iran.com/faqs/general-install/%d8%a7%d8%b3%d8%aa%d8%aa%d8%a7%d8%b1-%d9%81%db%8c%d8%b2%db%8c%da%a9%db%8c-%d8%af%d8%b3%d8%aa%da%af%d8%a7%d9%87-%d8%a7%d8%b3%d8%aa%d8%a7%d8%b1%d9%84%db%8c%d9%86%da%a9/). It's only available in Persian.

<!-- REVIEWS-->
<div class="reviews" markdown>
<span class="label">User reviews</span>

<!-- add reviews here -->
</div>

</div>

---

- [**E-SIM**](#) 
    - Using an eSIM allows you to activate a foreign mobile data plan without needing to insert a physical card into your device. It enables you to switch between different mobile networks and access alternative providers that may still be operational, ensuring connectivity even when local networks are restricted. However, it may not be a good solution in areas with complete network outages or where all providers are affected.

- [**Iodine**](https://www.kali.org/tools/iodine/) 
    - This is a piece of software that lets you tunnel IPv4 data through a DNS server. This can be usable in different situations where internet access is firewalled, but DNS queries are allowed.
    - <span style="color:red; font-style:italic;">Require a relatively higher level of technical expertise and proficiency in using the terminal.</span>

- [**Satellite Internet**](https://en.wikipedia.org/wiki/Satellite_Internet_access)

There are a few satellite internet providers on the market. When making a decision, consider factors such as usability, legality, cost, and latency. Please be aware of the [risks associated with satellite internet](https://satellitesafety.openinternetproject.org/). If you prefer not to be detected while using satellite internet, be cautious of RF emissions and unplug the device when not in use.

| Provider   | Speed Range                     | Starting Monthly Cost | Regular Monthly Cost | Contract                          | Monthly Equipment Costs               | Data Cap                     | Owned By                     |
|------------|----------------------------------|-----------------------|----------------------|-----------------------------------|---------------------------------------|-------------------------------|------------------------------|
| Hughesnet  | 25-100 Mbps download, 5 Mbps upload | $50-$95               | $75-$120             | 2 years                           | $10-$20 a month or $300-$450 one-time purchase | Unlimited, 100-200 GB (soft cap) |  [EchoStar](https://www.echostar.com) |
| Starlink   | 100-350 Mbps download, 5-25 Mbps upload | $80-$120              | $80-$120             | | $349 (currently discounted to $89) one-time purchase for Standard | Unlimited                            |  [SpaceX](https://www.spacex.com) |
| Viasat     | 25-150 Mbps download, 3 Mbps upload | $70-$100              | $70-$100             | None                              | $15 or $250 one-time purchase         | Unlimited, 850 GB (soft cap) |  [Viasat Inc.](https://www.viasat.com) |



## App Store
- [**Second Wind**](https://secondwind.guardianproject.info/en/repo)

<img src="icons/fdriod.png" alt="fdroid" class="tiny-icon" /> 
Second Wind is an offline distribution system for Android apps 

- [**Paskoocheh**](https://paskoocheh.com/?platform=macos) 

<img src="icons/fdriod.png" alt="fdroid" class="tiny-icon" />

Paskoocheh, Persian for “alleyway,” is an app store for Iranians to access tools for secure communication, information sharing, and censorship circumvention.

<!--
## Archiving & Secure Storage

- [**Save (Open Archive)**](#) - **Lorem Ipsum**.
-->

## Browser
- [**Ceno Browser**](https://ceno.app/en/index.html) 
    - Ceno Browser is a mobile web browser that uses peer-to-peer (P2P) technology to share and cache websites among users, allowing access to information even during internet shutdowns or in restricted regions. 
    - <span style="color:red; font-style:italic;">As this tool utilizes BitTorrent technology, please be aware that your IP address may be exposed to other users on the network, including potential monitoring by government agencies.</span>
    - <img src="icons/ios.png" alt="iOS" class="tiny-icon" /> <img src="icons/android.png" alt="Android" class="tiny-icon" /> <img src="icons/microsoft.png" alt="microsoft" class="tiny-icon" />

- [**Tor**](#) - The Tor Browser is a privacy-focused web browser that routes internet traffic through the Tor network, anonymizing users' online activities. It bypasses censorship by allowing access to blocked sites through encrypted connections.

## Camera
- [**eyeWitness to Atrocities**](https://www.eyewitness.global/) 
    - The eyeWitness to Atrocities app lets you capture photos and videos with embedded metadata to verify their authenticity in court.
    - <img src="icons/android.png" alt="Android" class="tiny-icon" />

- [**Tella**](https://tella-app.org/) 
    - <img src="icons/ios.png" alt="iOS" class="tiny-icon" /> <img src="icons/android.png" alt="Android" class="tiny-icon" /> <img src="icons/fdriod.png" alt="fdroid" class="tiny-icon" />
    - Take photos, record videos and audio directly in Tella so that your files are immediately encrypted and hidden in the app, to prevent authorities from finding photos or videos on phone album. 


## Content Distribution
- [**451 tools**](https://451.tools/) 
    - 451 Tools is an open-source solution to help publishers combat internet censorship or shutdowns. It includes a WordPress plugin and a JavaScript library that that utilize content caching directly on users’ devices.
- [**RelaySMS**](https://relay.smswithoutborders.com/) 
    - RelaySMS enables users to send messages to online platforms, including twitter, Gmail,  telegram, without the use of an active internet connection via encrypted SMS.
    - <span style="color:red; font-style:italic;">Authorities will be able to see a large amount of ciphertext being sent from your number, especially when your SIM is registered with your ID.</span>


## File Sharing
- [**Android Nearby Share**](#) - Quick Share, <span style="color:red; font-style:italic;">exclusive to Samsung devices</span>, uses Wi-Fi Direct for fast file sharing. Activate Quick Share in settings, select the file, and then choose nearby Samsung devices to instantly send images, videos, and files without internet connectivity. 
- [**NFC**](#) -NFC (Near Field Communication) file sharing on Android allows devices to exchange files by simply bringing them close together. Users enable NFC in settings, select the file to share, and tap the devices, initiating the transfer securely and swiftly.
- [**USB Dead Drops**](#) - A USB dead drop is a USB storage device installed in a public space. For example, a USB flash drive might be mounted in an outdoor brick wall and fixed in place with fast concrete. The dead drops can therefore be regarded as an anonymous, offline, peer-to-peer file sharing network.
- [**Tella**](https://tella-app.org/) 
    - <img src="icons/ios.png" alt="iOS" class="tiny-icon" /> <img src="icons/android.png" alt="Android" class="tiny-icon" /> <img src="icons/fdriod.png" alt="fdroid" class="tiny-icon" />
    - Tella's Nearby Sharing feature allows users to securely share end-to-end encrypted files fully offline, across platforms and devices.
- [**F-Droid Nearby (Android Beam)**](https://f-droid.org/en/packages/org.fdroid.nearby/) - F-Droid Nearby is a the built-in Nearby feature of the F-Droid client app that allows users to exchange apps device-to-device locally without internet access. 

## Hardware
- [**Butterbox**](https://likebutter.app/) 
    - Butter Box broadcasts a local WiFi network, allowing users to install Butter, access apps, and join public or private chatrooms. It operates without an internet connection, enabling app downloads and chatroom access directly from the Butter Box.
    - <span style="color:red; font-style:italic;">Has not been throughoutly tested</span>

## Media Authentication
- [**proofmode**](https://proofmode.org/) - Free and open-source camera app with built-in provenance and authentication for chain of custody. 

## Metadata Removal
Metadata is **“data about data”** - information that describes or gives context about a file, without being part of its main content. For example, date and time a photo was taken, location where a photo or video was taken, etc. 

Removing metadata protects human rights defenders by hiding file origins, locations, and identities, preventing surveillance or attacks, and ensuring the safety and confidentiality of activists, witnesses, and vulnerable communities.

- [**ExifEraser**](https://github.com/Tommy-Geenexus/exif-eraser)  
  Android app to remove metadata from pictures.  
  <img src="icons/android.png" alt="Android" class="tiny-icon" />

- [**Scrambled Exif**](https://gitlab.com/juanitobananas/scrambled-exif)  
  Android app to remove metadata, available on F-Droid.  
  <img src="icons/android.png" alt="Android" class="tiny-icon" /> <img src="icons/fdriod.png" alt="F-Droid" class="tiny-icon" />

- [**mat2**](https://github.com/tpet/mat2)  
  Command-line tool for removing metadata from a variety of file formats.

- [**ExifTool**](https://exiftool.org/)  
  Platform-independent Perl library and command-line application for reading, writing, and editing metadata in many file types.

## Offline Map
- [**OsmAnd**](https://osmand.net/) - OsmAnd is an offline world map application based on OpenStreetMap (OSM), which allows users to navigate taking into account the preferred roads and vehicle dimensions. OsmAnd is an open source app and they do not collect user data.

<!--
## Steganography Tool
- [**OpenPuff**](#) - **Lorem Ipsum**.
- [**Steghide**](#) - **Lorem Ipsum**.
- [**SilentEye**](#) - **Lorem Ipsum**.
- [**Crypture**](#) - **Lorem Ipsum**.
- [**Stegano**](#) - **Lorem Ipsum**.
- [**DeepSound**](#) - **Lorem Ipsum**.
- [**Outguess**](#) - **Lorem Ipsum**.
- [**Camouflage**](#) - **Lorem Ipsum**.
-->

## VPN

There are multiple VPNs on the market, and we have not included all of them. Our standard criteria include providers that meet at least some of the following: open source, strong encryption, independent security audits, a no-logs policy, a track record of supporting human rights, and not being owned by data mining companies. However, each VPN operates differently with various protocols. We recommend ensuring it works in your region.

 <span style="color:red; font-style:italic;">Using VPNs may be illegal in some countries. VPNs require a small amount of data to connect, making them ineffective during a full shutdown but potentially useful during throttling.</span>

| Provider   | Countries                          | Free Version? | Anonymous Payments     |
|------------|------------------------------------|---------------|------------------------|
| [**Proton**](https://protonvpn.com)       | 112+           | Yes           | Cash                   |
| [**IVPN**](https://www.ivpn.net)          | 37+            | No            | Monero, Cash           |
| [**Mullvad**](https://mullvad.net)        | 49+            | No            | Monero, Cash           |
| [**Psiphon**](https://psiphon.ca)         | 20+            | Yes           | No                     |
| [**Lantern**](https://getlantern.org)     | No customized server location | Yes           | No                     |
| [**Nym**](https://nymtech.net)            | 85             | No            | Monero                 |
| [**Tunnelbear**](https://www.tunnelbear.com) | 47          | Yes           | No                     |
| [**Orbot**](https://orbot.app/) | N/A     | Yes           | Free          |

---
## No longer supported
- [**goTenna Mesh**](#) - (no longer supported).