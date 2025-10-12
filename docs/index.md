# Shutdown Tools - Comprehensive Index

A collection of tools, websites, and strategies that could be used by HRDs, journalists, and activists **during internet outages and various types of network interference**.

If you would like to help in categorizing these projects, please submit a pull request to [this repo](https://github.com/stayteef/shutdown.tools).

----

## Table of Contents
1. [Understanding Internet Shutdown Types](#understanding-internet-shutdown-types)
2. [Tools by Shutdown Type](#tools-by-shutdown-type)
3. [All Tools by Category](#all-tools-by-category)

---

## Understanding Internet Shutdown Types

Based on Access Now's Taxonomy of Internet Shutdowns, there are **eight technical types** of internet shutdowns that authorities commonly implement. Understanding these types helps in selecting the right tools for circumvention.

### 1. **Full Blackout / Fundamental Infrastructure Shutdown**
**Description:** Complete shutdown caused by critical infrastructure manipulation - turning off power grids, cell towers, or broadband services. The most severe form where no internet connection is available.

**Symptoms:** 
- All websites immediately unreachable
- No internet connection available
- Mobile data and WiFi both down

**Detection Difficulty:** Easy to detect by users  
**Circumvention Difficulty:** Extremely difficult

---

### 2. **Routing Shutdown**
**Description:** BGP (Border Gateway Protocol) manipulation where ISPs drop or manipulate routing announcements, making networks unreachable. Traffic destined to specific IP addresses is deleted.

**Symptoms:**
- Specific networks or regions become unreachable
- Gradual degradation as routes propagate
- Some services work while others don't

**Detection Difficulty:** Medium (requires network analysis tools)  
**Circumvention Difficulty:** Medium to high

---

### 3. **DNS Manipulation**
**Description:** Authorities interfere with Domain Name System lookups through DNS hijacking, injection, or tampering, preventing domain names from resolving to correct IP addresses.

**Symptoms:**
- Websites don't load but direct IP access may work
- DNS lookup failures
- Incorrect websites loading (DNS spoofing)

**Detection Difficulty:** Easy with right tools  
**Circumvention Difficulty:** Low to medium

---

### 4. **Application-Based Blocking / Filtering**
**Description:** Commercial filtering appliances block access to specific platforms (Facebook, Twitter, WhatsApp) by examining metadata at the application layer. Most commonly used during protests and elections.

**Symptoms:**
- Specific social media or messaging apps don't work
- Other internet services function normally
- Error messages when accessing blocked platforms

**Detection Difficulty:** Easy  
**Circumvention Difficulty:** Low to medium

---

### 5. **Deep Packet Inspection (DPI)**
**Description:** Sophisticated traffic control examining packet headers AND data content, using predefined rules to block or allow traffic. Used in China's Great Firewall.

**Symptoms:**
- Searches for politically sensitive keywords fail
- Specific content blocked while related content works
- Slower internet connectivity
- Some parts of apps/websites don't work

**Detection Difficulty:** Medium  
**Circumvention Difficulty:** High

---

### 6. **Rogue Infrastructure Attack**
**Description:** Malicious infrastructure inserted into the network to intercept, modify, or block communications (e.g., IMSI catchers, rogue cell towers).

**Symptoms:**
- Unexpected disconnections
- Unusual device behavior
- Man-in-the-middle attacks

**Detection Difficulty:** High  
**Circumvention Difficulty:** High

---

### 7. **Denial of Service (DoS)**
**Description:** Overwhelming a web server or system with so many requests it slows down or crashes. Can target specific services or websites.

**Symptoms:**
- Specific websites/apps are slow or unresponsive
- Intermittent access - sometimes works, sometimes doesn't
- Performance degrades over time

**Detection Difficulty:** Medium  
**Circumvention Difficulty:** Low to medium

---

### 8. **Throttling**
**Description:** Artificially slowing down internet speeds to make services effectively unusable. Can be protocol-based or applied to all traffic. Often used to "hide" shutdowns.

**Symptoms:**
- Sluggish, slow, frustrating internet
- Downloads/uploads take much longer than normal
- Videos buffer constantly
- Apps timeout frequently

**Detection Difficulty:** Hard (difficult to distinguish from poor infrastructure)  
**Circumvention Difficulty:** Medium to high

---

## Tools by Shutdown Type

### Tools for Full Blackout / Infrastructure Shutdown
**Tags:** `#full-blackout` `#infrastructure-shutdown` `#offline-capable`

When all internet connectivity is severed, these tools enable communication and navigation:

**Communication:**
- **Briar** - Encrypted mesh networking via Bluetooth, Wi-Fi, Tor
- **Bridgefy** - Offline Bluetooth messaging
- **Meshtastic** - LoRa mesh networking (requires hardware)
- **Deku SMS** - Encrypted SMS communication

**Internet Alternatives:**
- **E-SIM** - Roaming from neighboring countries
- **Satellite Internet** - Starlink, Hughesnet, Viasat (expensive, detectable)
- **Foreign SIM Cards** - Connect to neighboring country infrastructure

**Navigation:**
- **OsmAnd** - Offline maps

**Hardware:**
- **Butterbox** - Local WiFi network for app distribution and chat

---

### Tools for Throttling
**Tags:** `#throttling` `#bandwidth-restriction` `#slow-internet`

When internet is deliberately slowed down:

**Circumvention:**
- **VPNs** (All listed) - May help if throttling is protocol-based
- **Tor Browser** - Route through Tor network
- **Iodine** - Tunnel IPv4 through DNS (technical expertise required)

**Content Delivery:**
- **451 Tools** - Content caching on user devices
- **RelaySMS** - Send to platforms via SMS without internet

---

### Tools for DNS Manipulation
**Tags:** `#dns-blocking` `#dns-manipulation` `#domain-blocking`

When domain names don't resolve correctly:

**Circumvention:**
- **Change DNS Configuration** - Use public DNS servers (Google DNS, Cloudflare, Quad9)
- **VPNs** (All listed) - Route DNS through VPN tunnel
- **Tor Browser** - Anonymous DNS resolution
- **Iodine** - DNS tunneling

---

### Tools for Application-Based Blocking / Filtering
**Tags:** `#app-blocking` `#social-media-blocking` `#platform-specific` `#filtering`

When specific apps or platforms (Facebook, WhatsApp, Twitter) are blocked:

**Circumvention:**
- **VPNs** (All listed) - Access blocked platforms
- **Tor Browser** - Access via browser (not native app)
- **Ceno Browser** - P2P browser for censored content

**Alternatives:**
- **Briar** - Alternative to mainstream messaging
- **JAMI** - Alternative communication platform
- **RelaySMS** - Access Gmail, Twitter, Telegram via SMS

**Content Distribution:**
- **451 Tools** - Bypass censorship with content caching

---

### Tools for Deep Packet Inspection (DPI)
**Tags:** `#dpi` `#deep-inspection` `#content-filtering` `#sophisticated-blocking`

When authorities examine packet contents to block specific data:

**Circumvention:**
- **Reliable VPNs** - Strong encryption (avoid common/blocked VPNs)
- **Tor Browser** - Encrypted, anonymous browsing
- **GoodbyeDPI / DPITunnel** - SNI filtering bypass
- **Protocol Obfuscation** - Hide VPN traffic type

**Communication:**
- **Briar** - Encrypted P2P messaging
- **Deku SMS** - Encrypted SMS (note: ciphertext visible to authorities)

---

### Tools for Denial of Service (DoS)
**Tags:** `#dos` `#ddos` `#service-unavailable`

When specific services are overwhelmed:

**Circumvention:**
- **VPNs** (All listed) - Access from different country
- **Direct IP Access** - Visit IP address instead of domain name
- **Tor Browser** - Route around attacks

**Content Caching:**
- **Ceno Browser** - P2P cached content
- **451 Tools** - Cached website content

---

### Tools for Routing Shutdown
**Tags:** `#routing` `#bgp-manipulation` `#network-unreachable`

When network routing is manipulated:

**Circumvention:**
- **VPNs** (All listed) - Route around affected networks
- **Satellite Internet** - Bypass terrestrial routing
- **Foreign SIM / E-SIM** - Use alternative network infrastructure
- **Tor Browser** - Multiple routing paths

---

### Tools for Localized Shutdowns
**Tags:** `#localized` `#geographic-blocking` `#zone-specific`

When shutdowns target specific geographic areas:

**Circumvention:**
- **Foreign SIM / E-SIM** - Connect to infrastructure outside zone
- **Satellite Internet** - Bypass local infrastructure
- **VPNs** - Appear to be outside affected region

**Communication:**
- **Briar** - Local mesh networking
- **Bridgefy** - Bluetooth mesh
- **Meshtastic** - LoRa mesh (long range)

---

## All Tools by Category

### Alternative Internet
**Useful for:** `#full-blackout` `#infrastructure-shutdown` `#localized` `#routing`

- **[E-SIM]()**
  - Activate foreign mobile data plan without physical card
  - Switch between networks
  - **Limitations:** Doesn't work in complete network outages
  - <img src="icons/esim.png" alt="eSIM" class="tiny-icon" />

- **[Iodine](https://www.kali.org/tools/iodine/)**
  - Tunnel IPv4 data through DNS server
  - Bypasses firewalls that allow DNS queries
  - **Limitations:** Requires technical expertise and terminal proficiency
  - <span style="color:red; font-style:italic;">Requires relatively higher level of technical expertise</span>

- **[Satellite Internet](https://en.wikipedia.org/wiki/Satellite_Internet_access)**
  - Providers: Starlink, Hughesnet, Viasat
  - **Considerations:** Cost, legality, latency, RF detectability
  - **Warning:** [Understand risks](https://satellitesafety.openinternetproject.org/) - RF emissions can reveal usage
  - <span style="color:red; font-style:italic;">Expensive, detectable via RF emissions. Unplug when not in use if avoiding detection.</span>

| Provider   | Speed Range                     | Starting Monthly Cost | Regular Monthly Cost | Contract | Monthly Equipment Costs | Data Cap | Owned By |
|------------|----------------------------------|-----------------------|----------------------|----------|------------------------|----------|----------|
| Hughesnet  | 25-100 Mbps down, 5 Mbps up | $50-$95 | $75-$120 | 2 years | $10-$20/month or $300-$450 one-time | Unlimited, 100-200 GB soft cap | [EchoStar](https://www.echostar.com) |
| Starlink   | 100-350 Mbps down, 5-25 Mbps up | $80-$120 | $80-$120 | None | $349 ($89 discounted) one-time | Unlimited | [SpaceX](https://www.spacex.com) |
| Viasat     | 25-150 Mbps down, 3 Mbps up | $70-$100 | $70-$100 | None | $15 or $250 one-time | Unlimited, 850 GB soft cap | [Viasat Inc.](https://www.viasat.com) |

---

### App Store
**Useful for:** `#full-blackout` `#offline-capable` `#app-distribution`

- **[Second Wind](https://secondwind.guardianproject.info/en/repo)**
  - Offline distribution system for Android apps
  - <img src="icons/fdriod.png" alt="F-Droid" class="tiny-icon" />

- **[Paskoocheh](https://paskoocheh.com/?platform=macos)**
  - App store for Iranians
  - Access tools for secure communication, information sharing, censorship circumvention
  - <img src="icons/fdriod.png" alt="F-Droid" class="tiny-icon" />

---

### Browser
**Useful for:** `#filtering` `#app-blocking` `#dns-manipulation` `#censorship` `#dpi`

- **[Ceno Browser](https://ceno.app/en/index.html)**
  - P2P browser sharing and caching websites among users
  - Works during shutdowns in restricted regions
  - **Tags:** `#filtering` `#app-blocking` `#dos` `#censorship`
  - <span style="color:red; font-style:italic;">Uses BitTorrent - your IP may be exposed to other users and government monitoring</span>
  - <img src="icons/ios.png" alt="iOS" class="tiny-icon" /> <img src="icons/android.png" alt="Android" class="tiny-icon" /> <img src="icons/microsoft.png" alt="Windows" class="tiny-icon" />

- **[Tor Browser](https://www.torproject.org/)**
  - Privacy-focused browser routing through Tor network
  - Anonymizes online activities
  - Bypasses censorship with encrypted connections
  - **Tags:** `#filtering` `#app-blocking` `#dns-manipulation` `#dpi` `#throttling`
  - **Considerations:** Slower than regular browsing, may be blocked in some countries
  - <span style="color:red; font-style:italic;">VPN use may be illegal in some countries. ISPs can detect VPN/Tor usage.</span>
  - <img src="icons/windows.png" alt="Windows" class="tiny-icon" /> <img src="icons/apple.png" alt="macOS" class="tiny-icon" /> <img src="icons/linux.png" alt="Linux" class="tiny-icon" /> <img src="icons/android.png" alt="Android" class="tiny-icon" />

---

### Camera
**Useful for:** `#documentation` `#evidence-collection` (works offline)

- **[eyeWitness to Atrocities](https://www.eyewitness.global/)**
  - Capture photos/videos with embedded metadata
  - Verifiable authenticity for court evidence
  - <img src="icons/android.png" alt="Android" class="tiny-icon" />

- **[Tella](https://tella-app.org/)**
  - Encrypted photo, video, audio capture
  - Files immediately encrypted and hidden
  - Prevents authorities from finding evidence
  - **Tags:** `#full-blackout` `#offline-capable`
  - <img src="icons/ios.png" alt="iOS" class="tiny-icon" /> <img src="icons/android.png" alt="Android" class="tiny-icon" /> <img src="icons/fdriod.png" alt="F-Droid" class="tiny-icon" />

---

### Communication
**Useful for:** `#full-blackout` `#filtering` `#app-blocking` `#localized` `#offline-capable`

- **[Briar](https://briarproject.org/)**
  - Censorship-resistant P2P messaging
  - Connects via Bluetooth, Wi-Fi, or Tor
  - No centralized servers
  - **Tags:** `#full-blackout` `#filtering` `#app-blocking` `#dpi` `#localized` `#offline-capable`
  - Available: [Android](https://play.google.com/store/apps/details?id=org.briarproject.briar.android), [F-Droid](https://briarproject.org/fdroid)
  - <img src="icons/android.png" alt="Android" class="tiny-icon" /> <img src="icons/fdriod.png" alt="F-Droid" class="tiny-icon" />

- **[Bridgefy](https://bridgefy.me/)**
  - Free messaging without internet
  - Bluetooth mesh networking
  - **Tags:** `#full-blackout` `#localized` `#offline-capable`
  - Available: [Android](https://play.google.com/store/apps/details?id=me.bridgefy.main), [iOS](https://apps.apple.com/us/app/bridgefy-offline-messages/id975776347)
  - <img src="icons/ios.png" alt="iOS" class="tiny-icon" /> <img src="icons/android.png" alt="Android" class="tiny-icon" />

- **[Deku SMS](https://dekusms.com/)**
  - Android SMS app with encryption
  - **Tags:** `#full-blackout` `#throttling` `#offline-capable`
  - <span style="color:red; font-style:italic;">Authorities will see large ciphertext from your number, especially if SIM registered to your ID</span>
  - <img src="icons/android.png" alt="Android" class="tiny-icon" />

- **[JAMI](https://jami.net/)**
  - Distributed communication platform
  - P2P encrypted calls and messaging
  - **Tags:** `#filtering` `#app-blocking` `#offline-capable`
  - <img src="icons/windows.png" alt="Windows" class="tiny-icon" /> <img src="icons/apple.png" alt="macOS" class="tiny-icon" /> <img src="icons/linux.png" alt="Linux" class="tiny-icon" /> <img src="icons/ios.png" alt="iOS" class="tiny-icon" /> <img src="icons/android.png" alt="Android" class="tiny-icon" />

- **[Meshtastic](https://meshtastic.org/)**
  - Decentralized wireless off-grid mesh networking
  - LoRa protocol on low-power devices
  - Communicate without internet using LoRa technology
  - **Tags:** `#full-blackout` `#localized` `#offline-capable`
  - <span style="color:red; font-style:italic;">Requires purchasing physical LoRa device</span>
  - <img src="icons/ios.png" alt="iOS" class="tiny-icon" /> <img src="icons/android.png" alt="Android" class="tiny-icon" />

#### Communication Tools Comparison

| Chat App    | Bluetooth | Wi-Fi | LoRa | SMS | Internet | Images/Files | Open Source | Requires Device |
|-------------|-----------|-------|------|-----|----------|--------------|-------------|-----------------|
| Briar       | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ✔️ | ✔️ | ❌ |
| Bridgefy    | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ✔️ | ❌ | ❌ |
| JAMI        | ✔️ | ✔️ | ❌ | ❌ | ✔️ | ✔️ | ✔️ | ❌ |
| Deku SMS    | ❌ | ❌ | ❌ | ✔️ | ❌ | ✔️ | ✔️ | ❌ |
| Meshtastic  | ✔️ | ✔️ | ✔️ | ❌ | ❌ | ❌ | ✔️ | ✔️ |

---

### Content Distribution
**Useful for:** `#filtering` `#app-blocking` `#censorship` `#throttling`

- **[451 Tools](https://451.tools/)**
  - Open-source solution for publishers
  - Combat censorship/shutdowns
  - WordPress plugin & JavaScript library
  - Content caching on users' devices
  - **Tags:** `#filtering` `#app-blocking` `#dos` `#throttling`

- **[RelaySMS](https://relay.smswithoutborders.com/)**
  - Send messages to online platforms via encrypted SMS
  - Works without internet: Twitter, Gmail, Telegram
  - **Tags:** `#full-blackout` `#throttling` `#filtering`
  - <span style="color:red; font-style:italic;">Authorities will see ciphertext from your number, especially if SIM registered to your ID</span>

---

### File Sharing
**Useful for:** `#full-blackout` `#localized` `#offline-capable`

- **[Android Nearby Share / Quick Share]()**
  - Wi-Fi Direct for fast file sharing
  - **Tags:** `#full-blackout` `#localized` `#offline-capable`
  - <span style="color:red; font-style:italic;">Quick Share exclusive to Samsung devices</span>
  - <img src="icons/android.png" alt="Android" class="tiny-icon" />

- **[NFC File Sharing]()**
  - Near Field Communication
  - Exchange files by bringing devices close together
  - **Tags:** `#full-blackout` `#localized` `#offline-capable`
  - <img src="icons/android.png" alt="Android" class="tiny-icon" />

- **[USB Dead Drops]()**
  - USB storage in public spaces
  - Anonymous, offline, P2P file sharing
  - **Tags:** `#full-blackout` `#offline-capable`

- **[Tella](https://tella-app.org/)**
  - Nearby Sharing feature
  - Secure E2E encrypted file sharing
  - Fully offline, cross-platform
  - **Tags:** `#full-blackout` `#localized` `#offline-capable`
  - <img src="icons/ios.png" alt="iOS" class="tiny-icon" /> <img src="icons/android.png" alt="Android" class="tiny-icon" /> <img src="icons/fdriod.png" alt="F-Droid" class="tiny-icon" />

- **[F-Droid Nearby (Android Beam)](https://f-droid.org/en/packages/org.fdroid.nearby/)**
  - Built-in F-Droid feature
  - Exchange apps device-to-device
  - No internet required
  - **Tags:** `#full-blackout` `#offline-capable`
  - <img src="icons/android.png" alt="Android" class="tiny-icon" /> <img src="icons/fdriod.png" alt="F-Droid" class="tiny-icon" />

---

### Hardware
**Useful for:** `#full-blackout` `#localized` `#offline-capable`

- **[Butterbox](https://likebutter.app/)**
  - Local WiFi network broadcaster
  - Install apps, access chatrooms
  - Works without internet
  - App downloads and chatrooms directly from Butter Box
  - **Tags:** `#full-blackout` `#localized` `#offline-capable`
  - <span style="color:red; font-style:italic;">Has not been thoroughly tested</span>

---

### Media Authentication
**Useful for:** `#documentation` `#evidence-collection` (works during any shutdown)

- **[proofmode](https://proofmode.org/)**
  - Free open-source camera app
  - Built-in provenance and authentication
  - Chain of custody for evidence
  - <img src="icons/android.png" alt="Android" class="tiny-icon" />

---

### Metadata Removal
**Useful for:** `#privacy` `#security` (works offline, important before/during shutdowns)

**What is Metadata?** "Data about data" - information describing or giving context to a file. Examples: date/time photo taken, GPS location, camera model, device information.

**Why Remove Metadata?** Protects HRDs by hiding file origins, locations, and identities. Prevents surveillance, attacks, and ensures safety of activists, witnesses, and vulnerable communities.

- **[ExifEraser](https://github.com/Tommy-Geenexus/exif-eraser)**
  - Android app to remove metadata from pictures
  - <img src="icons/android.png" alt="Android" class="tiny-icon" />

- **[Scrambled Exif](https://gitlab.com/juanitobananas/scrambled-exif)**
  - Android app to remove metadata
  - Available on F-Droid
  - <img src="icons/android.png" alt="Android" class="tiny-icon" /> <img src="icons/fdriod.png" alt="F-Droid" class="tiny-icon" />

- **[mat2](https://github.com/tpet/mat2)**
  - Command-line tool
  - Removes metadata from various file formats
  - <img src="icons/linux.png" alt="Linux" class="tiny-icon" />

- **[ExifTool](https://exiftool.org/)**
  - Platform-independent Perl library
  - Command-line application
  - Read, write, edit metadata in many file types
  - <img src="icons/windows.png" alt="Windows" class="tiny-icon" /> <img src="icons/apple.png" alt="macOS" class="tiny-icon" /> <img src="icons/linux.png" alt="Linux" class="tiny-icon" />

---

### Offline Map
**Useful for:** `#full-blackout` `#navigation` `#offline-capable`

- **[OsmAnd](https://osmand.net/)**
  - Offline world map based on OpenStreetMap
  - Navigate with preferred roads and vehicle dimensions
  - Open source, no user data collection
  - **Tags:** `#full-blackout` `#offline-capable`
  - <img src="icons/ios.png" alt="iOS" class="tiny-icon" /> <img src="icons/android.png" alt="Android" class="tiny-icon" />

---

### VPN
**Useful for:** `#throttling` `#filtering` `#app-blocking` `#dns-manipulation` `#dpi` `#routing`

Multiple VPNs available. Selection criteria: open source, strong encryption, independent security audits, no-logs policy, human rights track record, not owned by data mining companies.

<span style="color:red; font-style:italic;">VPN use may be illegal in some countries. VPNs require small data amount to connect - ineffective during full shutdown but useful during throttling.</span>

**Selection Guidelines:**
- Verify VPN works in your region before shutdown
- Download multiple VPNs in advance
- Choose open source with transparent security reviews
- Check no-logs policy and jurisdiction
- [EFF VPN Selection Guide](https://www.eff.org/deeplinks/2017/07/choosing-vpn-thats-right-you)

**Important Notes:**
- ISPs can detect VPN usage
- VPNs only effective if some connectivity exists
- Consider legal risks in your jurisdiction

| Provider | Countries | Free Version? | Open Source | Independent Audit | Notes |
|----------|-----------|---------------|-------------|-------------------|-------|
| [Provider data to be filled in] | | | | | |

---

## Quick Reference: Shutdown Type → Recommended Tools

### Full Blackout
**First Priority:** Briar, Bridgefy, Meshtastic, OsmAnd  
**If Possible:** Satellite Internet, Foreign SIM, E-SIM

### Throttling
**First Priority:** VPNs, Tor Browser  
**Alternatives:** 451 Tools, RelaySMS, Iodine

### DNS Manipulation
**First Priority:** Change DNS, VPNs  
**Alternatives:** Tor Browser, Direct IP access

### Application Blocking
**First Priority:** VPNs, Tor Browser  
**Alternatives:** Briar, JAMI, RelaySMS, Ceno Browser

### DPI (Deep Packet Inspection)
**First Priority:** Reliable VPNs (obscure), Tor Browser  
**Advanced:** GoodbyeDPI, DPITunnel, Protocol Obfuscation

### Denial of Service
**First Priority:** VPNs, Tor Browser  
**Alternatives:** Ceno Browser, 451 Tools, Direct IP

### Routing Shutdown
**First Priority:** VPNs, Satellite Internet  
**Alternatives:** Foreign SIM, E-SIM, Tor Browser

### Localized Shutdown
**First Priority:** Foreign SIM, E-SIM  
**Alternatives:** Briar, Bridgefy, Meshtastic, VPNs

---

## Tags Index

- `#full-blackout` - Complete infrastructure shutdown
- `#infrastructure-shutdown` - Physical infrastructure disruption
- `#throttling` - Bandwidth restriction and slowdown
- `#dns-manipulation` - Domain name system interference
- `#dns-blocking` - Domain name blocking
- `#filtering` - Application/content filtering
- `#app-blocking` - Specific application blocking
- `#platform-specific` - Platform-targeted blocking
- `#dpi` - Deep packet inspection
- `#routing` - BGP/routing manipulation
- `#dos` - Denial of service attacks
- `#ddos` - Distributed denial of service
- `#localized` - Geographic/zone-specific shutdowns
- `#offline-capable` - Works completely offline
- `#censorship` - General censorship circumvention
- `#documentation` - Evidence and documentation tools
- `#privacy` - Privacy-enhancing tools
- `#security` - Security tools

---

## Before a Shutdown: Preparation Checklist

1. **Download Multiple Tools:**
   - At least 2-3 VPNs
   - Tor Browser
   - Offline messaging apps (Briar, Bridgefy)
   - Offline maps (OsmAnd)
   - F-Droid and Second Wind for app distribution

2. **Test Everything:**
   - Verify VPNs connect and work
   - Test offline communication tools with contacts
   - Download offline map data for your region
   - Practice using circumvention tools

3. **Backup Communications:**
   - Exchange Briar contact info with key people
   - Set up Meshtastic devices if possible
   - Note direct IP addresses of important services
   - Share alternative DNS server addresses

4. **Documentation Ready:**
   - Install Tella, eyeWitness, or proofmode
   - Remove metadata from sensitive files
   - Backup important data offline

5. **Know Your Rights:**
   - Research VPN legality in your jurisdiction
   - Understand risks of circumvention
   - Have legal support contacts ready

---

## Additional Resources

- **[Access Now Digital Security Helpline](https://www.accessnow.org/help/)** - 24/7 assistance during shutdowns
- **[Access Now #KeepItOn Coalition](https://www.accessnow.org/keepiton/)** - Global coalition fighting shutdowns
- **[OONI Probe](https://ooni.org/)** - Measure internet censorship
- **[Internet Outage Detection and Analysis (IODA)](https://ioda.caida.org/)** - Detect and analyze outages
- **[Taxonomy of Internet Shutdowns PDF](https://www.accessnow.org/)** - Technical deep dive

---

**Last Updated:** October 2025  
**Maintained by:** shutdown.tools community  
**License:** Open for public use

---

## Appendix A: Detection and Monitoring Tools

### Organizations Monitoring Internet Shutdowns

- **[Internet Outage Detection and Analysis (IODA)](https://ioda.caida.org/)** - CAIDA system for detecting and documenting internet outages
- **[RIPE NCC](https://www.ripe.net/)** - Network coordination center with routing data
- **[Oracle Internet Intelligence Map](https://map.internetintel.oracle.com/)** - Real-time internet disruption monitoring
- **[Google Product Traffic Data](https://transparencyreport.google.com/traffic/)** - Google Transparency Reports on traffic
- **[M-Lab](https://www.measurementlab.net/)** - Open internet measurement data
- **[Route Views Project](http://www.routeviews.org/)** - BGP routing data archive
- **[OONI (Open Observatory of Network Interference)](https://ooni.org/)** - Network measurement and censorship detection

### Detection Tools You Can Use

- **[OONI Probe](https://ooni.org/install/)** - Measure internet censorship on your device
- **[Snoopsnitch](https://opensource.srlabs.de/projects/snoopsnitch)** - Detect IMSI catchers and mobile network attacks (Android)
- **[Network Measurement Tools](https://www.measurementlab.net/tests/)** - Test your connection for interference

---

## Appendix B: Understanding Network Layers

### Where Shutdowns Are Implemented

Understanding where in the network infrastructure a shutdown is implemented helps assess impact and choose appropriate tools.

#### Public Switched Telephone Network (PSTN)
Traditional telephone infrastructure - cell towers, landlines, SMS. Shutdowns here affect:
- Voice calls
- SMS/text messages  
- Mobile data (if cell towers shut down)
- Landline internet

**Impact:** Affects basic communication, including emergency services

#### Internet Layer
Modern internet infrastructure - ISPs, backbone networks, routing. Shutdowns here affect:
- Web browsing
- Apps requiring internet
- Email, social media
- VoIP calls
- Online services

**Impact:** Affects most modern communication but SMS may still work

---

## Appendix C: Scope and Scale of Shutdowns

### Scope: What Is Affected

**Geographic Scope:**
- **National** - Entire country
- **Regional** - State, province, or large area
- **Local** - City, town, neighborhood
- **Venue-specific** - Single building, event space, protest area

**Service Scope:**
- **Total blackout** - All internet and mobile services
- **Mobile only** - Cell networks down, broadband may work
- **Broadband only** - Home/office internet down, mobile may work
- **Platform-specific** - Only certain apps/websites blocked
- **International only** - Can't access foreign sites

### Scale: How Many Are Affected

Consider both:
1. **Population of affected area** - How many people normally there
2. **Current population** - May be higher during protests, events, elections

**Examples:**
- Nationwide in large country: Hundreds of millions affected
- Regional shutdown during protests: Tens of millions affected  
- Local shutdown at polling stations: Thousands to millions affected
- Venue-specific (e.g., train system): Hundreds to thousands affected

---

## Appendix D: Detailed Shutdown Scenarios & Mitigation Strategies

### Scenario 1: Complete Infrastructure Shutdown During Protests

**Situation:** Government turns off cell towers and broadband in protest area

**Symptoms:**
- No mobile signal
- No WiFi connectivity
- Complete blackout

**Recommended Response:**
1. **Immediate:** Switch to Briar/Bridgefy for local communication via Bluetooth
2. **If prepared:** Activate Meshtastic devices for longer-range mesh
3. **Navigation:** Use OsmAnd offline maps
4. **If near border:** Try foreign SIM to connect to neighboring infrastructure
5. **Documentation:** Continue using Tella to capture encrypted evidence offline

**Preparation needed:** Install apps beforehand, exchange contact info, download maps

---

### Scenario 2: Social Media Blocking During Elections

**Situation:** Facebook, Twitter, WhatsApp, Instagram blocked via filtering

**Symptoms:**
- Specific apps show errors or won't load
- Other internet services work fine
- Browser access to platforms fails

**Recommended Response:**
1. **First attempt:** Connect VPN and retry platforms
2. **If VPN blocked:** Use Tor Browser to access via web interface (not native apps)
3. **Alternative communication:** Switch to Briar, JAMI, or Signal (if not blocked)
4. **Content sharing:** Use RelaySMS to post via SMS
5. **Access cached content:** Use Ceno Browser for cached versions

**Note:** Must use platforms via browser when using VPN/Tor, native apps may not work

---

### Scenario 3: DNS Manipulation of News Websites

**Situation:** News websites won't load but other sites work

**Symptoms:**
- Specific domains don't resolve
- "DNS lookup failed" errors
- Wrong websites load (DNS spoofing)

**Recommended Response:**
1. **Change DNS settings** to public DNS (Cloudflare 1.1.1.1, Google 8.8.8.8)
2. **If that fails:** Connect to VPN which provides its own DNS
3. **Direct access:** Try accessing site by IP address instead of domain name
4. **Alternative:** Use Tor Browser for anonymous DNS resolution

**How to change DNS:**
- **Android:** Settings > Network > Private DNS
- **iOS:** Use DNS configuration profile or VPN
- **Windows:** Network settings > Adapter options > DNS servers
- **macOS:** System Preferences > Network > DNS

---

### Scenario 4: Deep Packet Inspection Blocking VPNs

**Situation:** Common VPNs don't work, keyword searches fail

**Symptoms:**
- Popular VPNs can't connect
- Specific search terms return no results
- Parts of websites don't load
- Internet generally slower

**Recommended Response:**
1. **Use obscure VPNs** - Less common providers more likely to work
2. **Protocol obfuscation** - Use VPNs with obfuscation features (hide VPN traffic)
3. **Advanced tools:** GoodbyeDPI, DPITunnel, Zapret for SNI filtering bypass
4. **Tor with bridges** - Use Tor with bridge relays to hide Tor usage
5. **Different ISP:** If possible, try smaller ISPs that may not have DPI

**Technical users can:**
- Set up personal VPN server abroad
- Use SSH tunneling
- Deploy domain fronting techniques

---

### Scenario 5: Throttling During Peak Political Events

**Situation:** Internet works but extremely slow, effectively unusable

**Symptoms:**
- Everything loads very slowly
- Frequent timeouts
- Videos won't stream
- Apps constantly buffer

**Recommended Response:**
1. **Test with VPN** - See if speeds improve (suggests protocol-based throttling)
2. **Switch protocols** - Try different connection methods (mobile vs broadband)
3. **Lightweight options:** Use text-only versions of sites, disable images
4. **SMS alternatives:** Use RelaySMS, Deku SMS for basic communication
5. **Content caching:** 451 Tools may help for pre-cached content
6. **Different ISP:** If available, try alternative provider

**Difficult to bypass if all traffic throttled** - May need satellite or alternative infrastructure

---

### Scenario 6: Localized Shutdown at Protest March

**Situation:** Internet works elsewhere but not at protest location

**Symptoms:**
- No connectivity at specific location
- Works when you leave the area
- May affect specific blocks or zone

**Recommended Response:**
1. **Mesh networks:** Activate Briar, Bridgefy for local P2P communication
2. **If near edge:** Move to zone boundary, use foreign SIM if near border
3. **Long-range mesh:** Meshtastic with LoRa can communicate several kilometers
4. **Document offline:** Use Tella, eyeWitness to capture evidence
5. **Relay information:** People entering/leaving zone can relay messages

**Key strategy:** Pre-coordinate meeting points outside affected zone

---

### Scenario 7: Denial of Service on Human Rights Website

**Situation:** Specific organization's website slow/unreachable

**Symptoms:**
- One site extremely slow or down
- Other sites work normally
- Sometimes loads, sometimes doesn't

**Recommended Response:**
1. **VPN to different country** - Access site as if from abroad
2. **Try IP address** - Visit site's IP instead of domain name
3. **Cached versions:** Use Ceno Browser or web caches
4. **Mirror sites:** Look for mirror/backup sites announced on social media
5. **Contact organization:** They may have alternative access methods

**For website owners:** Have backup hosting, use CDN, prepare mirror sites

---

## Appendix E: Legal and Safety Considerations

### Legal Risks by Jurisdiction

**Countries Where VPN Use May Be Illegal or Restricted:**
- Belarus
- China  
- Egypt
- Iran
- Iraq
- North Korea
- Oman
- Russia
- Syria
- Turkey
- Turkmenistan
- Uganda
- United Arab Emirates
- Venezuela

**Important:** Laws change frequently. Research current laws in your jurisdiction.

### Operational Security Considerations

**Using VPNs/Tor:**
- ✓ ISPs CAN see you're using VPN/Tor (even if they can't see content)
- ✓ VPN providers CAN see your traffic (choose no-logs provider)
- ✓ Traffic pattern analysis may still identify you
- ✓ Government may treat VPN usage as suspicious

**Using Mesh Networks:**
- ✓ Requires proximity to other users
- ✓ May be detectable via radio scanning (Bluetooth, WiFi, LoRa)
- ✓ Meshtastic/LoRa especially detectable with RF scanners
- ✓ Using unique protocols may draw attention

**Using Satellite Internet:**
- ✓ Highly detectable via RF emissions
- ✓ Authorities can locate terminals
- ✓ May be illegal without authorization
- ✓ Expensive and requires advance setup

**Using Encrypted SMS:**
- ✓ Authorities see large amounts of ciphertext from your number
- ✓ If SIM registered to your ID, you're identifiable
- ✓ Pattern of encrypted messages may draw attention
- ✓ Consider using unregistered SIM if legal

### Threat Modeling

**Ask yourself:**
1. What am I trying to protect? (communications, identity, location)
2. Who am I protecting it from? (government, ISP, third parties)
3. What are consequences if I fail? (arrest, harassment, violence)
4. How likely is the threat? (constant monitoring vs. targeted surveillance)
5. What resources does adversary have? (local police vs. nation-state)

**Match tools to threat level:**
- Low threat: VPN may be sufficient
- Medium threat: Tor + encrypted messaging
- High threat: Mesh networks, operational security protocols
- Extreme threat: Avoid electronic communication, use human couriers

---

## Appendix F: Testing and Verification Before Shutdowns

### Test Your Tools Before You Need Them

**VPN Testing:**
```
1. Install 3 different VPN providers
2. Test each one connects successfully
3. Visit blocked/slow sites to verify they work
4. Check speed with speedtest while connected
5. Verify DNS leaks aren't occurring
6. Test on both mobile data and WiFi
```

**Mesh Network Testing:**
```
1. Install Briar/Bridgefy on multiple devices
2. Exchange contact information
3. Turn OFF WiFi and mobile data
4. Test messaging via Bluetooth
5. Test at various distances
6. Verify file sharing works
7. Practice with your trusted contacts
```

**Offline Preparation:**
```
1. Download OsmAnd and offline maps for your region
2. Test navigation works with GPS only (airplane mode)
3. Install Tella and practice capturing encrypted media
4. Download F-Droid and Second Wind repos
5. Save offline copies of important documents
6. Export contact information from phone
```

**Documentation Tools:**
```
1. Install and test proofmode, eyeWitness, or Tella camera
2. Verify metadata is captured correctly
3. Practice encrypting and exfiltrating evidence
4. Set up secure backup locations
5. Test metadata removal tools
```

### Create Emergency Communication Plan

**Share with trusted contacts:**
- Primary: [Normal internet - Signal, WhatsApp, etc.]
- Secondary: [VPN/Tor access to platforms]
- Tertiary: [Briar contact ID for mesh networking]
- Quaternary: [Physical meetup locations and times]
- Emergency: [Phone numbers for SMS/voice]

**Establish protocols:**
- Check-in schedule (every X hours)
- Code words for different situations
- Designated relay points
- Safe/danger signals

---

## Appendix G: Platform-Specific Circumvention Guide

### Accessing Social Media During Blocking

| Platform | Native App | Browser + VPN | Browser + Tor | SMS Gateway | Alternative |
|----------|-----------|---------------|---------------|-------------|-------------|
| Facebook | ❌ Blocked | ✓ Works | ✓ Works | ❌ None | Briar, JAMI |
| Twitter/X | ❌ Blocked | ✓ Works | ✓ Works | ✓ RelaySMS | Mastodon |
| WhatsApp | ❌ Blocked | ⚠️ Limited | ⚠️ Limited | ❌ None | Signal, Briar |
| Instagram | ❌ Blocked | ✓ Works | ✓ Works | ❌ None | Pixelfed |
| Telegram | ❌ Blocked | ✓ Works | ✓ Works | ✓ RelaySMS | Signal |
| Signal | ⚠️ May work | ✓ Works | ✓ Works | ❌ None | Briar |
| Gmail | ⚠️ May work | ✓ Works | ✓ Works | ✓ RelaySMS | ProtonMail |

**Legend:**
- ✓ Works: Generally functional
- ⚠️ Limited: Reduced functionality  
- ❌ Blocked: Won't work

**Key Insight:** When using VPN/Tor, access platforms via web browser, not native apps. Native apps may have hardcoded servers that remain blocked.

---

## Appendix H: Shutdown Response Checklist

### When a Shutdown Begins

**Immediate Actions (First 5 minutes):**
- [ ] Identify what's affected (all internet, specific apps, mobile vs broadband)
- [ ] Test with multiple devices if available
- [ ] Note exact time shutdown began
- [ ] Take screenshots of error messages
- [ ] Notify trusted contacts while possible

**Assessment Phase (5-30 minutes):**
- [ ] Determine shutdown type using symptom guide
- [ ] Check if VPN/Tor already installed and working
- [ ] Test alternative connectivity (mobile if broadband down, vice versa)
- [ ] Switch to offline communication tools if needed
- [ ] Activate mesh network apps

**Response Phase (30+ minutes):**
- [ ] Implement appropriate circumvention for shutdown type
- [ ] Establish communication with network using working tools
- [ ] Begin documentation if witnessing events
- [ ] Share information about shutdown type and circumvention
- [ ] Monitor for changes in shutdown method

**Documentation Phase (Ongoing):**
- [ ] Run OONI Probe tests when safe
- [ ] Document timestamps and what's blocked
- [ ] Save evidence of shutdown impacts
- [ ] Report to Access Now #KeepItOn coalition
- [ ] Share information with monitoring organizations

---

## Appendix I: Country-Specific Notes

### High-Risk Environments

**China:**
- Extensive DPI and Great Firewall
- Most VPNs blocked
- Tor largely blocked
- Advanced preparation essential
- Consider Snowflake/Meek bridges for Tor

**Iran:**
- DNS manipulation common
- Social media regularly blocked
- Mobile networks often throttled
- Satellite internet illegal
- Heavy monitoring of circumvention

**Myanmar:**
- Frequent long-duration blackouts
- Military control of infrastructure
- Mobile networks often primary target
- Mesh networks especially valuable
- International border areas may have connectivity

**Russia:**
- Increasingly sophisticated blocking
- VPN restrictions growing
- Tor partially blocked
- Domestic alternatives promoted
- Protocol-based throttling

**Ethiopia:**
- Regional shutdowns during conflicts
- Complete blackouts lasting months
- Limited advance warning
- Mesh networks and offline tools critical
- Border regions may access neighboring infrastructure

**India:**
- Frequent localized shutdowns
- Often targets Kashmir and protest areas
- Usually temporary (hours to days)
- Mobile networks primarily affected
- VPNs generally work

---

## Appendix J: Advanced Technical Information

### DNS Configuration Details

**Recommended Public DNS Servers:**

Primary Options:
- **Cloudflare:** 1.1.1.1, 1.0.0.1 (privacy-focused)
- **Google:** 8.8.8.8, 8.8.4.4 (reliable, but Google knows your queries)
- **Quad9:** 9.9.9.9 (blocks malicious domains)
- **OpenDNS:** 208.67.222.222, 208.67.220.220

DNS over HTTPS (DoH) / DNS over TLS (DoT):
- More resistant to manipulation
- Encrypts DNS queries
- Supported by modern browsers
- May be blocked in some countries

**Configuration:**
- Changing device DNS helps with basic DNS blocking
- Won't help with DNS injection/spoofing
- VPN/Tor provides more robust DNS protection

### Port and Protocol Information

**Common Blocking Targets:**
- HTTP (80), HTTPS (443) - Web traffic
- DNS (53) - Domain lookups
- SMTP (25, 587) - Email sending
- IMAP (143, 993) - Email receiving
- OpenVPN (1194, 443) - VPN traffic
- WireGuard (51820) - Modern VPN
- Tor (9001, 9030) - Tor network

**Circumvention Strategies:**
- Port 443 often less blocked (HTTPS traffic)
- Protocol obfuscation makes VPN look like HTTPS
- Tor bridges hide Tor usage
- SSH tunneling on port 22 sometimes works

---

## Appendix K: Community and Support Resources

### Organizations Fighting Shutdowns

- **[Access Now](https://www.accessnow.org/)** - #KeepItOn campaign, 24/7 Digital Security Helpline
- **[Internet Society (ISOC)](https://www.internetsociety.org/)** - Internet advocacy and policy
- **[Electronic Frontier Foundation (EFF)](https://www.eff.org/)** - Digital rights advocacy
- **[Reporters Without Borders (RSF)](https://rsf.org/)** - Press freedom
- **[ARTICLE 19](https://www.article19.org/)** - Freedom of expression
- **[Open Observatory of Network Interference (OONI)](https://ooni.org/)** - Measurement and documentation
- **[Ranking Digital Rights](https://rankingdigitalrights.org/)** - Corporate accountability
- **[The Tor Project](https://www.torproject.org/)** - Anonymity and circumvention

### Getting Help During Shutdowns

**Access Now Digital Security Helpline:**
- **Email:** help@accessnow.org
- **PGP:** Available on website
- **Signal:** Available on website  
- **Available:** 24/7 in multiple languages
- **Services:** Secure communication advice, circumvention assistance, documentation support

**Regional Organizations:**
- Africa: [Various regional digital rights groups]
- Asia: [Various regional digital rights groups]
- Latin America: Derechos Digitales, InternetBolivia, R3D
- Middle East: [Various regional digital rights groups]

### Training and Education

- **[Security in a Box](https://securityinabox.org/)** - Digital security guide
- **[Surveillance Self-Defense](https://ssd.eff.org/)** - EFF security guides
- **[Digital First Aid Kit](https://digitalfirstaid.org/)** - Emergency response guide
- **[Access Now Helpline Resources](https://www.accessnow.org/help/)** - Security guides and tools

---

## Appendix L: Contributing to This Resource

### How to Help

**Submit Tool Suggestions:**
- Create GitHub issue or pull request
- Include: tool name, URL, description, shutdown types it helps with
- Specify platforms (iOS, Android, Windows, etc.)
- Note any risks or limitations

**Update Information:**
- Tool links that have changed
- New features in existing tools
- Legal status changes in different countries
- New shutdown techniques observed

**Add Country-Specific Information:**
- Common shutdown patterns in your country
- Effective circumvention methods
- Legal considerations
- Regional support resources

**Improve Documentation:**
- Clarify confusing sections
- Add examples and use cases
- Translate to other languages
- Create visual guides

**Share Your Experience:**
- What worked during actual shutdowns
- What didn't work and why
- Lessons learned
- Preparation recommendations

### Repository Information

- **GitHub:** [https://github.com/stayteef/shutdown.tools](https://github.com/stayteef/shutdown.tools)
- **License:** Open for public use and contribution
- **Maintainers:** shutdown.tools community
- **Updates:** Regularly maintained and reviewed

---

**Remember:** The best time to prepare for a shutdown is before it happens. Download tools, test them, share knowledge with your community, and stay safe.

**Last Updated:** October 2025  
**Version:** 2.0 Comprehensive  
**Maintained by:** shutdown.tools community  
**License:** Open for public use