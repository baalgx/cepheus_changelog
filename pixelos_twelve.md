# PixelOS Device Changes | 13-July-2022
- *SIGNED BUILD [switch to release-keys], NEEDS CLEAN FLASH!
- CarrierConfig: Enable VoLTE support for Telkomsel (Indonesia)
- overlay: enable VoLTE support for Indosat and XL Axiata
- overlay: enable VoLTE support for Three
- dsds: restart qcrild on data switch (restores VoLTE switching in real time)
- Add and increase 5 GHz network signal tolerance
- gps: Update to LA.UM.9.1.r1-11200-SMxxx0.0
- Update telephony package list to LA.QSSI.12.0.r1-05600-qssi.0
- configs: Update config.fs from LA.UM.9.1.r1-10600-SMxxx0.0
- Spoof Netflix as Pixel 6
- Switch to raven Pixel 6 Pro fingerprint [test]
- parts: Add Mi Sound Enhancer (Dirac) and Clear Speaker
- parts: Add more Dirac presets and fixes for Dirac


# PixelOS Device Changes | 08-July-2022
- overlay: Compact cached app heaps in the background
- overlay: Allow more cached apps in the background
- rootdir: Add SchedTune configuration
- Switch to SkiaGL Threaded
- Developer options: Display cutout: add NoCutOut overlay (Hide Notch) 
   [It breaks fingerprint at the moment]
- Bring back HBM / Display Mode
- LiveDisplay: Add Picture adjustment
- kernel: Drop KCAL color control
- kernel: Fix green tint issue on fod unlock [Thanks to Logan, Flackback and Demon000 for commit/fix!]
- kernel: Enable LZ4 Compressed Ramdisk
- Other improvements!

# PixelOS Device Changes | 28-June-2022
- Drop Vulkan (fixes color/glitched video issues and some GCam crashing)
- Disable zram writeback 
- rootdir: Powersaving in charger mode
- Adjust charger state CPUs
- CarrierConfig: update from 5800 QSSI
- Enable LZ4 compression for ramdisks
- Use coral tuning for columbus feature
- Properties: remove obsolete debug.sf.disable_backpressure
- Fixed status bar glitch for apps that access internal resource dimen
- Revert "Import governor settings from coral"
- Revert "Add SchedTune configuration"
- Revert "Import power_profile from coral"
- Nuke init.power.rc
- Don't tune sde partition on boot
- overlay: Disable Adaptive Connectivity preference
- overlay: Enable auto brightness while dozing
- AOD: Decouple suspend from screen state
- wifi: Update config from sm8150-common tree 
- prop: Force disable iorapd
- Other improvements

# PixelOS Device Changes | 17-June-2022
- Initial Build, PixelOS bringup.
- Use SOVIET kernel (bringup by Niviann).
- Update Adreno Drivers to 530
- Switch to proton clang
- Switch back to QTI Bluetooth stack
- Bring back Aptx HD/Adaptive
