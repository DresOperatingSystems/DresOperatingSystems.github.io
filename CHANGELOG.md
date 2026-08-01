## August 1, 2026

### Added
- New update entry for microG v3.1.5 and WebView v2.2.1, covering the bundled app automation going live, the pinned signing keys, and what is planned next
- Modules tab now states the plan: an automatic build and release workflow for the WebView module

### Changed
- Module versions and download links moved to WebView v2.2.1 and microG v3.1.5 on the modules tab, the welcome tab and the projects tab
- microG module card rewritten around what v3.1.5 changes rather than v3.1.4
- Modules tab intro and the projects tab entry now describe the modules as the two the system needs, rather than as automation of build steps

## July 30, 2026

### Added
- New update entry covering DresSecureComms 1.8.1, the scan engine gaining the option to send a file to VirusTotal, the coming automation on the module repos, and the short break before the Linux distro build starts
- DresOS-WebView added to the GitHub Projects tab, the one repository that was missing from it

### Changed
- Star counts refreshed from the GitHub API across every listed repository: guide 26 to 29, Magisk Modules 16 to 18, Android-Degoogling 7 to 11, Third-Party-Kali-Nethunter-Build 8 to 9, DresSecureComms now listed at 23
- Third-Party-Kali-Nethunter-Build and kali-linux-private-network-setup now marked archived, which they are
- DresTermuxAI link repointed at The DresOS Foundation, which is where it now lives
- Versions brought current everywhere: DresSecureComms 1.8.0 to 1.8.1 and microG v3.1.3 to v3.1.4, including the module download link and the module card description
- microG module card no longer lists DroidGuard Helper, as microG folded it into GmsCore upstream and it is not bundled
- Terms of service privacy section now states that file scanning uploads a file only when you choose to send that one file, since the app can now do that
- The retired defensive app suite wording replaced in the Welcome and DresOS Android tabs
- Distro tab and the Welcome tab now say the same thing about when the distro build starts
- Open Graph and Twitter descriptions no longer mention bots, which we no longer run
- Confirmed working devices now include the Google Pixel 9 Pro XL on LineageOS 23.2 and the Samsung Galaxy J6 (J600F) on stock Android 10 with One UI 2.0
- The standalone DresOS WebView APK is no longer described as being on IzzyOnDroid or having Obtainium support. It is too large for IzzyOnDroid, so its own GitHub releases page is the only place it is distributed, and both the module card and the June 19 announcement now say that and link to it

## July 23, 2026

### Changed

Updated our terms of service to fit within the current Dres ecosystem, updated the DresOS Android tab around the actual system repo along with other minor website changes.

## July 18, 2026

### Changed
- made major announcement
- updated website to fit in around the new major announcement

## July 5, 2026

### Changed
- Replaced the two wallpapers with the new DresOS lock and circuit designs, now self-hosted in the repo under images/ instead of an external image host
- Link preview (Open Graph and Twitter card) now uses a dedicated 1200x630 preview built from the circuit design, self hosted on dresos.org

## July 3, 2026

### Changed
- Rebranded across the site: DresOperatingSystems is now The DresOS Foundation (header, meta author, footer copyright, license block)
- Canonical URL moved to https://dresos.org (og:url, license block); contact email is now security@dresos.org
- The DresOS Android guide repository links repointed at github.com/The-DresOS-Foundation; every other repository link stays on the original account until those repos complete the move
- Magisk Modules tab info block corrected: DresSecureComms was never shut down, the system ships as Magisk modules and standalone FOSS apps
- Welcome and GitHub Projects current-release mentions bumped to DresOS microG v3.1.1
- DresSecureComms cards updated for v1.6.0: SMS and MMS picture messaging, IzzyOnDroid link added alongside GitHub
- Styling consolidated: the site theme now lives in styles.css and is linked from index.html, replacing the stale unused stylesheet and the inline style block; malformed CSS and HTML lines normalised

### Added
- New July 3, 2026 Updates entry covering The DresOS Foundation organisation move, the dresos.org domain and security@dresos.org address, DresSecureComms 1.6.0 (end-to-end picture messaging, instant sent-message history, larger in-call controls, notification Copy action, IzzyOnDroid listing, clean VirusTotal scan, PGP/age/SSH ED25519 signing roadmap, Fossify thanks), and DresOS microG v3.1.1 (Google-signed path removed, honest version-aware signature spoofing guidance)
- GitHub Projects tab note explaining the organisation move and that old links redirect
- Fake Traveler credit in the July 3 update entry: the mock location components are built on references from their application
- URL Check credit in the July 3 update entry: for the scan part that connects to VirusTotal, which our scan engine was built from

### Removed
- Motorola-moto-g32-recovery-mode listing from GitHub Projects
- All HTML comments across the page

## June 5, 2026

### Changed
- DresOS Android tab: added the Motorola Moto g32 video demo (Streamable embed, phone-proportioned) above the build guide links, with Watch on Ko-fi and Open Video buttons
- Magisk Modules tab: dresosmicrog module card updated to v3.0.0 - pure file overlay, no Zygisk and no LSPosed, ROM-provided signature spoofing, GmsCore 0.3.15, Aurora Services as a priv-app for silent installs, bootloop-safe; download link now points at microg-v3.0.0
- Welcome "What we do" bullet and GitHub Projects blurb: current releases updated to AOSmium WebView v2.2.0 and DresOS microG v3.0.0
- Updates tab: the May 25 microG entry was trimmed of the unreleased v2.1.0 and v2.2.0 roadmap and the Noogle naming; the Aurora Services note now points to the v3.0.0 resolution
- DresOS Defensive App Suite: every version-pinned download link replaced with a stable F-Droid package page or GitHub releases-latest link
- "What the System Includes": app suite count updated from 16 to 19

### Added
- New June 5, 2026 Updates entry announcing the DresOS microG v3.0.0 rebuild and the guide refresh (Aves Libre gallery, Stratum 2FA, Tuta Calendar, HeliBoard design, link audit, video demo)
- DresOS Defensive App Suite cards for Aves Libre (gallery), Stratum (offline 2FA), and Tuta Calendar (encrypted calendar)

## May 25, 2026

### Changed
- Magisk Modules tab: DresOS microG (`dresosmicrog`) moved from Planned Modules to Released Modules
  - Module card v2.0.0 description added: systemless microG suite, single flash, bundled Zygisk sigspoof on arm64 + x86_64, runtime debloat via pm disable-user, per component bootloop sentinel, ROM autodetection for Calyx/iode/eOS/Lineage for microG
  - Lists every bundled package: GmsCore 0.3.7.250932, Companion (FakeStore), GsfProxy, DroidGuard Helper, Aurora Store
  - Calls out the v2.0.0 known issue (Aurora Privileged Extension does not always land as system priv-app) and the v2.1.0 / v2.2.0 roadmap
- Welcome section "What we do" bullet updated: now reads "Current releases: AOSmium WebView v2.1.0, DresOS microG v2.0.0. Next module in development: Permissions Hardener (dresosperms)."
- GitHub Projects section: DresOS-Magisk-Modules description updated to "Current releases: AOSmium WebView v2.1.0 and DresOS microG v2.0.0. Permissions Hardener in development."
- Module Repository row: replaced "Latest Release" button with two explicit links: "AOSmium Latest" pointing at the AOSmium release tag and "microG Latest" pointing at microg-v2.0.0

### Added
- New May 25, 2026 update entry at the top of the Updates section detailing the DresOS microG v2.0.0 release: bundled microG suite, Zygisk signature spoof scoped to the microG process, same partition staging, cert verified self heal, runtime debloat, per component bootloop sentinel, known Aurora Privileged Extension issue and the v2.1.0 / v2.2.0 roadmap
- New Donate section in the Welcome tab with the Ko-fi button and a short explanation of where the funds go (test devices, hosting, developer time on the next Magisk module)
- Footer donate link to ko-fi.com/dresos so the donation path is reachable from every tab

## May 15, 2026

### Changed
- AOSmium WebView module card updated from v1.0.0 to v2.1.0:
  - Description rewritten to reflect new activation pipeline (static RRO + systemless bind mount + cmd webviewupdate, with dumpsys verification)
  - Removed references to pm install, Magisk .replace files, and manual selection in Developer Options
  - Added a requirements line
- Welcome section "What we do" bullet updated: now reads "Current release: AOSmium WebView v2.1.0. Next module in development: MicroG (dresosmicrog)."
- GitHub Projects section: DresOS-Magisk-Modules description updated from "First release: AOSmium WebView v1.0.0" to "Current release: AOSmium WebView v2.1.0. MicroG module in development."

### Added
- Confirmed working devices list under AOSmium WebView module card:
  - Motorola Moto G32 on LineageOS Android 15
  - Motorola ThinkPhone on Stock Android 15
  - Motorola Moto G7 Plus on Stock Android 10
  - Motorola Moto G7 Plus on LineageOS Android 15
  - Samsung Galaxy A05s on Stock Android 10
- New May 15, 2026 update entry at the top of the Updates section detailing:
  - AOSmium v2.1.0 rewrite of the activation pipeline
  - Root cause of the v1.0.0 Pixel 9 bootloop (pm install plus .replace markers removing the fallback provider)
  - Root cause of the v1.2.x silent activation failure (plain text overlay manifest, wrong target package)
  - New three step activation pipeline (RRO plus bind mount plus cmd webviewupdate)
  - Two layers of bootloop safety (post-fs-data sentinel and inert mode flag)
  - Confirmed working devices list
  - Announcement that work begins next on the MicroG module (dresosmicrog)

## May 12, 2026

### Changed
- Replaced DresEcoVerse tab with Updates tab in navigation
- Removed all references to DresEcoVerse across the site:
  - Welcome section: removed EcoVerse bullet point from "What we do" list
  - Security Distro section: replaced EcoVerse devlog reference with Updates tab direction
  - Terms of Service: removed "(including the DresEcoVerse)" and "in the EcoVerse" phrasing
  - Contact section: removed entire Community/EcoVerse contact card
  - Footer: removed @DresosIbot link (Contact section already has bot as button)
- Updated language to confirm Magisk modules are already released
- Clarified that @DresosIbot is the only official DresOS Telegram presence; users should verify links via this website

### Added
- Updates section with three chronological entries:
  1. **May 12, 2026** - First official website update: DresEcoVerse archived, centralized website now active, Magisk Modules already released, app list integrated into DresOS Android guide, @DresosIbot as sole official Telegram presence
  2. **April 30, 2026** - Message to supporters regarding organizational shift, ZeusAI sister organization announcement with ⚡ ZeusAI button link
  3. **April 30, 2026** - Call to action supporting Keep Android Open initiative with official links to keepandroidopen.org
