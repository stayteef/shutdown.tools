# Shutdown Tools 

A collection of tools, websites, strategies that could be used by HRDs, journalists, and anyone, **during internet outages**. 

If you would like to help in categorising these projects, please submit a pull request to [this repo](https://github.com/stayteef/shutdown.tools).

----
## Alternative Internet

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

## Communication
- [**Briar**](https://briarproject.org/) 
    - Censorship-resistant peer-to-peer messaging that bypasses centralized servers. Briar allows you to privately connect via Bluetooth, Wi-Fi or Tor. Available on [Android](https://play.google.com/store/apps/details?id=org.briarproject.briar.android), [F-Droid](https://briarproject.org/fdroid). 

- [**Bridgefy**](https://bridgefy.me/) 
    - Bridgefy is a free messaging app that works without the Internet.Available on [Android](https://play.google.com/store/apps/details?id=me.bridgefy.main), [iOS](https://apps.apple.com/us/app/bridgefy-offline-messages/id975776347).

- [**Deku SMS**](https://dekusms.com/)
     - DekuSMS is an Android SMS app that allows you to encrypt your SMS.
     - <span style="color:red; font-style:italic;">Requires purchasing a physical device.</span>

- [**JAMI**](#) 
    - **Lorem Ipsum**.

- [**Meshtastic**](https://meshtastic.org/)
     - Meshtastic is a decentralized wireless off-grid mesh networking LoRa protocol that operates on low-power devices. It enables users to communicate with their app using LoRa technology without an internet connection.
     - <span style="color:red; font-style:italic;">Requires purchasing a physical device.</span>

| Chat App    | Bluetooth | Wi-Fi | LoRa | SMS | Internet | Images/Files Sharing | Open Source | Requires Physical Device |
|-------------|-----------|-------|------|-----|----------|----------------------|-------------|-------------------------|
| Briar       | ✔️         | ✔️     | ❌    | ❌   | ✔️        | ✔️                    | ✔️           | ❌                       |
| Bridgefy    | ✔️         | ✔️     | ❌    | ❌   | ✔️        | ✔️                    | ❌           | ❌                       |
| JAMI        | ✔️         | ✔️     | ❌    | ❌   |         | ✔️                    | ✔️           | ❌                       |
| Deku SMS    | ❌         | ❌     | ❌    | ✔️   | ❌        | ✔️                    | ✔️           | ❌                       |
| Meshtastic  | ✔️         | ✔️     | ✔️    | ❌   | ❌        | ❌                    | ✔️           | ✔️                       |


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