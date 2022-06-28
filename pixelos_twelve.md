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
