## [Unreleased]

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

## [Unreleased]

### Changed
- AOSmium WebView module card updated from v1.0.0 to v2.1.0:
  - Description rewritten to reflect new activation pipeline (static RRO + systemless bind mount + cmd webviewupdate, with dumpsys verification)
  - Removed references to pm install, Magisk .replace files, and manual selection in Developer Options
  - Added requirements line (Magisk 24.0+, Android 10-15, arm/arm64)
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

## Previous Unreleased

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
