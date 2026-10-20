# Gabriel Peralta

Embedded, hardware and software projects.

## Projects

### LOTBOT: Autonomous Search Rover
Co-developed as a team project. A 4WD rover that maps rooms with LiDAR (SLAM Toolbox), navigates with ROS 2 Nav2 on a Raspberry Pi 5 and finds objects named in plain text using YOLOE detection, controlled from a web panel on a phone or laptop. An STM32 safety bridge with a watchdog and command deadlines gave zero roll-on across 100 traced stops. 180 automated tests, odometry error of about 1.3%, and 14 of 23 bench searches found.

`ROS 2` `Raspberry Pi 5` `STM32` `YOLOE` `Python`

### Custom USB MIDI Controller
A USB MIDI/HID DJ controller built around an STM32G0B1, with a capacitive touch jog wheel and 12 addressable RGB LEDs. Six KiCad revisions to a JLCPCB assembly-ready board. Low-level C firmware for touch sensing, hardware timers and USB HID/MIDI descriptors, prototyped on breadboards and verified with an Analog Discovery 2.

`STM32` `C` `KiCad` `USB MIDI` `PCB design`

### AutoTier · [autotier.ca](https://autotier.ca)
A Canadian vehicle comparison web app. Reduced a 7,000+ row dataset to about 350 deduplicated models rated on safety, recalls, fuel economy, winter readiness and theft risk. Dynamic category routes with fuzzy matching, and a Python script that repairs missing drivetrain data.

`React` `Vite` `TanStack Router` `Tailwind CSS` `Supabase` `Python`

### [Easykeeps website](https://github.com/gperalta-dev/EasyKeeps) · [easykeeps.ca](https://easykeeps.ca)
A landing page for a small-business bookkeeping service in plain HTML, CSS and JavaScript with no build step. Separate phone layouts, pinned scroll scenes, animated sample charts, an accessibility panel and full reduced-motion support. Published to GitHub Pages by GitHub Actions.

`HTML` `CSS` `JavaScript` `GitHub Actions`

### Easykeeps Automation
Python automations for a bookkeeping month end, connected to QuickBooks Online, Gmail and Google Drive. They suggest transaction categories, prepare GST/HST worksheets, read receipt photos with the Claude API and match them to expenses, check bank reconciliations and build monthly client reports. A supervisor watches every run and sends Discord alerts. A person approves anything before it goes into the books.

`Python` `QuickBooks API` `Claude API` `Google APIs`

### Smash Simulator Discord Bot
A Discord bot that builds a whole server from one config file and syncs roles from Roblox Game Passes and game progress. It also guards against nuking: it watches the audit log, quarantines anyone who goes past set limits, rebuilds what they broke and locks the server down during raids.

`Node.js` `Discord API` `Roblox` `Docker`

### Claude Command Center
A live board of every Claude Code session across my machines, viewable from a phone. Hooks on each machine report events to a hub that streams them over WebSocket to an installable web app, and events queue up while the hub is offline.

`TypeScript` `React` `Vite` `WebSocket` `PWA`
