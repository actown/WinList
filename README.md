# Windows Software
Over the years I've found a number of useful Windows tools and software. Here's my attempt to write them down. If you have any tools/software that you recommend, please make a Pull Request and I will merge it! Try to keep all the software Open Source or free unless there isn't an equal alternative.

First step is to use [Ninite](https://ninite.com/) to install most of the software you need. None of the software on the list is provided via Ninite.


## Tools

### Dealing with Drivers
- [DDU](https://www.wagnardsoft.com/display-driver-uninstaller-ddu-) - Full uninstall of display drivers.
- [DriverStoreExplorer](https://github.com/lostindark/DriverStoreExplorer) - Inspect the [Windows Driver Store](https://msdn.microsoft.com/en-us/library/ff544868(VS.85).aspx).
- [DriverView](https://www.nirsoft.net/utils/driverview.html) - View drivers are that loaded on your system currently.
- [Snappy Driver Installer](https://sdi-tool.org/) - Useful tool to install drivers. Not super easy to use, but it can get the job done.

### Bluescreen Tools
- [BlueScreenView](https://www.nirsoft.net/utils/blue_screen_view.html) - If you have minidumps enabled on bluescreen then this is the tool you'll want to use.

### Network Tools
- [Wireshark](https://www.wireshark.org/) - Packet capture and network analyzer.
- [TCPView](https://docs.microsoft.com/en-us/sysinternals/downloads/tcpview) - netstat but Windows.
- [WinMTR](https://sourceforge.net/projects/winmtr/) - Network trace route monitoring. mtr but Windows.
- [mitmproxy](https://mitmproxy.org/) - HTTP/HTTPS man in the middle proxy. Useful to debug app that use http/https.

### Others
- [Autoruns](https://docs.microsoft.com/en-us/sysinternals/downloads/autoruns) - Lets you modify programs and drivers that autorun on your system.
- [Process Explorer](https://docs.microsoft.com/en-us/sysinternals/downloads/process-explorer) - Task Manager but better.
- [BleachBit](https://www.bleachbit.org/) - Open source replacement for CCleaner. Great for cleaning up logs and other cruft. Enable "Download and update cleaners from community" in the settings to support a ton more apps for cleaning.
- [USB Device Tree Viewer](https://www.uwe-sieber.de/usbtreeview_e.html) - View the device tree for your USB hubs.
- [HxD Hex Editor](https://mh-nexus.de/en/hxd/) - Windows hex editor.
- [hashcat](https://hashcat.net/hashcat/) - Password cracking using GPUs.
- [WinDirStat](https://windirstat.net/) - Disk usage statistics viewer.
- [Chocolatey](https://chocolatey.org/) - Package manager for Windows
- [TeraCopy](https://www.codesector.com/teracopy) - Replacement for file transferring (instead of Explorer).

## Dealing with Telemetry and OS Tweaks

### Windows
- [ShutUp10](https://www.oo-software.com/en/shutup10) - Disable a lot of Windows "features".
- [Autofixer](https://utilitybox.org/autofixer) - One click to disable Windows features.
- [Ultimate Windows Tweaker](https://www.thewindowsclub.com/ultimate-windows-tweaker-4-windows-10) - Modify a lot of hidden Windows settings.
- [Winaero Tweaker](https://winaero.com/download.php?view.1796) - Modify more Windows settings.
- [Windows Privacy Dashboard](https://wpd.app/) - Manage privacy settings in Windows.

### Nvidia
- [Disable-Nvidia-Telemetry](https://github.com/Sleepydragn1/Disable-Nvidia-Telemetry) - Disable the Nvidia Telemetry. (Outdated)

### Theme Support
- [UltraUXThemePatcher](https://www.syssel.net/hoefs/software_uxtheme.php?lang=en) - Required for custom Windows themes.
- [OldNewExplorer](https://msfn.org/board/topic/170375-oldnewexplorer-118/) - Some changes for Explorer. Handy for themes.

### Themes
- [Penumbra 10](https://www.deviantart.com/scope10/art/Penumbra-10-Windows-10-visual-style-568740374) - Dark Windows 10 theme. Checkout Deviantart for more themes.
- [ShadowFox](https://overdodactyl.github.io/ShadowFox/) - Firefox Dark Theme. Works by modifying the base Firefox files.
- [Pressure For Steam](https://github.com/DirtDiglett/Pressure-for-Steam/tree/Steam-Client-Beta) - Steam dark theme.


## Benchmarks and Stress

### Stress testing
- [Prime95](https://www.mersenne.org/download/) - CPU stress test.
- [FurMark](https://geeks3d.com/furmark/) - GPU stress test. Take care if you use this, it will get your GPU hot!

### Benchmarks
- [UserBenchmark](https://www.userbenchmark.com/) - Great free benchmark. I recommend anyone who is having PC issues to run this.
- [3DMark](https://www.3dmark.com/) - NON-FREE. The standard for 3d benchmarks. You can usually get this cheap during a Steam sale.
- [Unigine Superposition](https://benchmark.unigine.com/superposition) - Unigine's latest benchmark. While this is the latest, the older benchmarks are still great. Free version for basic tests, paid version for more in-depth tests.
- [Final Fantasy XIV Benchmark](https://na.finalfantasyxiv.com/benchmark/) - FFXIV benchmark.

## Monitoring / Hardware Info
- [CoreTemp](https://www.alcpu.com/CoreTemp/) - Monitor your CPU temps.
- [HWMonitor](https://cpuid.com/softwares/hwmonitor.html) - Overall great hardware monitor.
- [HWiNFO](https://www.hwinfo.com/) - Sensors and hardware info all in one.
- [CPU-Z](https://www.cpuid.com/softwares/cpu-z.html) - CPU focused hardware info, but it does cover all hardware types.
- [GPU-Z](https://www.techpowerup.com/gpuz/) - GPU focused hardware info.


## Firefox / Browser
Some of these have Chrome equivalents or in some cases, they link to a website where you can download the addon for whatever your browser is.

### Addons
- [Cookie AutoDelete](https://addons.mozilla.org/en-US/firefox/addon/cookie-autodelete/) - Auto remove cookies.
- [Decentraleyes](https://decentraleyes.org/) - Serves CDN libraries from a local cache.
- [HTTPS Everywhere](https://www.eff.org/https-everywhere) - Uses HTTPS on sites that support it.
- [Stylus](https://add0n.com/stylus.html) - Enables website theming.
- [uBlock Origin](https://github.com/gorhill/uBlock#ublock-origin) - Web/Ad Blocking.
- [Violentmonkey](https://violentmonkey.github.io/) - Userscript support.
- [Privacy Badger](https://www.eff.org/privacybadger/) - Blocks website trackers.
- [The Great Suspender](https://github.com/deanoemcke/thegreatsuspender) - (Chrome) Automatic tab suspension to free up memory.

### Stylus Themes
- [Dark Hacker News](https://userstyles.org/styles/22794/a-dark-hacker-news) - Dark theme for Hacker News.
- [Amazon - Dark Slate](https://userstyles.org/styles/133725/amazon-dark-slate) - Dark theme for Amazon. Has some issues but works alright.
- [Dark LWN.net](https://userstyles.org/styles/164378/dark-lwn-net) - Dark theme for lwn.net.
- [Dark Stylus](https://github.com/overdodactyl/Stylus-Dark) - Dark theme for stylus addon.
- [GitHub Dark](https://github.com/StylishThemes/GitHub-Dark) - Dark theme for GitHub.
- [StackOverflow Dark](https://github.com/StylishThemes/StackOverflow-Dark) - Dark theme for StackOverflow.
- [Wikipedia Dark](https://github.com/StylishThemes/Wikipedia-Dark) - Dark theme for Wikipedia.
- [Twitter - Dark n Simple](https://userstyles.org/styles/128569/twitter-dark-n-simple) - Dark theme for Twitter.


## Misc
- [HashTab](http://implbits.com/products/hashtab/) - FREE for PERSONAL USE. Easy file hashsum checking in Windows.
- [Rufus](https://rufus.ie/) - Easy bootable USB creator tool.
- [Switch Hitter](https://www.elitekeyboards.com/switchhitter.php) - Keyboard switch tester.
- [Speedcrunch](https://speedcrunch.org/) - Calculator replacement.
- [ImageGlass](https://imageglass.org/) - Photo viewer replacement.
- [OBS Studio](https://obsproject.com/) - Streaming and/or screen recording.
- [Color Sustainer](https://www.guru3d.com/files_details/color_sustainer_download.html) - Forces ICC (color profiles) against certain (or all) display modes.


## Password Management
Use anything that works for you as long as you use something!


## Useful Links
- [USB3.0/3.1 Drivers](https://www.win-raid.com/t834f25-USB-Drivers-original-and-modded.html) - This site provides USB3.0/3.1 drivers for most chipsets. Easy way to switch to the vendor drivers instead of the Microsoft provided ones.
- [BSOD Analyst](https://carrona.org/dvrref.php) - Lots of useful info on this site for tracking down BSODs.
- [NirSoft](https://www.nirsoft.net/) - Tons of random useful tools.
