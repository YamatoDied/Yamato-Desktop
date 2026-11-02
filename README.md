## ⚡ YD Release 1.3: reliable, light, easy to start with

### 🕒 Clocks
- **Two independent widgets:** the digital clock (with its date) and the analog clock now have their own tab, switch, designs and settings. Turning one on or off never moves the other or the panels below, and each can be dragged on its own.
- **The date goes away with the digital clock.**
- **More designs:** 27 digital (was 16) and 12 analog (was 3 looks). "Like the template" keeps the old behaviour.
- **Digital settings:** seconds, 12/24 h, leading zero, blinking colons, font, colour (theme / accent / detail / custom) and 6 date formats.
- **Analog settings:** numerals on the dial (12·3·6·9, 1–12, Roman), marks (4 / 12 / 60 / none), date on the dial, second hand and smooth motion, dial colour.
- Old settings are migrated automatically.

### 🖼 Look
- **216 wallpapers** (was 162). Only 7 redraw every frame (was 52), so they are about 3× lighter on average (estimated).
- **48 palettes**, **13 editor window styles**, sorting, a Favorites filter and ECO / LOW / MID cost badges.

### 🧩 Widgets
- **New:** Weather (up to 5-day forecast) and Tasks with repeats (daily, weekly, monthly, one-time).
- **Faster:** Notes, Progress, System and Music do roughly 3× less work (modelled, not measured).
- **Battery** now covers Bluetooth devices and USB phones.

### 🚀 Easier to use
- **Quick Start** on first launch: 3 questions, 6 ready layouts.
- **"Lost?"** button: search every setting in plain words.
- Hotkeys tab, a hideable EDIT / EXIT panel, UA / EN from the first screen, and the AI replies in the language you write in.
- Auto-cleanup of `%LocalAppData%\YamatoDesktop` and a clean exit with no leftover processes.

### 🔒 Security
- Local endpoints require a header and a local Host check.
- Random XMRig API token on every run.
- Updates without a SHA-256 digest are rejected.

### ⛏ Optional mining
**Off by default and never starts without your own Monero wallet address.** XMRig is not bundled: Setup asks first (unchecked by default), and building from source fetches it for the Mining tab. Gentle defaults (5% CPU, Idle priority), monitoring, USD / EUR / UAH / PLN / GBP rates and an AFK mode. **Open dev fee: 1 minute per 100 minutes of active mining**, wallet address shown in the Mining tab. Don't want it? Just never enable it.

### 🌐 Network use
GitHub (updates). Open-Meteo and ipapi.co (only with the Weather widget). CoinGecko (only for mining rates). dl.google.com (Android platform-tools, only for USB phone battery).

### 📥 Install
Download **`YamatoDesktop-Release-1.3-Setup.exe`**, or unzip **`YD_Release_1.3.zip`** and run `Build.bat`. Auto-update from 1.2 picks up the zip.

### ⚠ Known limitations
- Battery level of 2.4 GHz dongle devices is not shown yet.
- Tested on one PC (Windows 10/11), so other setups may differ. Found a bug? Open an Issue.
