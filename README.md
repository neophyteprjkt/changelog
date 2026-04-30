# Changelog 01/05/'26:
* Use pie chromatix libs for better camera quality
* Disable forced encryption by default
* Disable sdm rotator downscaler
* Disable SystemUI anti-falsing on lockscreen

# Changelog 12/04/'26:
* Disable blurs by default
* Explicitly disable "Enable GL comp backpressure"
* Finetune statusbar padding
* Set Window animation/transition scale to 50%
* Adjust SurfaceFlinger sf/app duration
* enable ro.hwui.render_ahead and set it to 20 frames

# Changelog 05/04/'26:
* Update work durations from taro
* Do not prefer hw codecs in thumbnail previews
* Drop Dirac
* Bringback LunarisDolby
* Silence hwcomposer and HWUI logspam
* Reconfigure ZRAM
* Set default IRQ affinity for trinket
* Boost I/O performance during bootup
* Disable surfaceflinger prime shader cache conditionally
* Do not balance msm_drm and kgsl-3d0 IRQs
* Massively lower LCD thermal throttling
* Improve cpusets configuration
* Adjust keyboard height for better typing experience

# Changelog 20/01/'26:
* Drop qti thermal hal
* Change default GPU idle timeout to 60ms
* Increase launch boost to 5sec
* Support Wifi6
* Drop Dolby Atmos
* Bringback Dirac
* Update surface flinger timers and disable content detection for refresh rate
* set readahead_size_kb=128 to system, vendor, data

# Changelog 12/01/'26:
* Bringback Xiaomi Parts
* Bringback MiuiCamera
* Fix lag on recent app
* Fix litle cpu stuck in 1350mhz
* Switch to using LunarisDolby
* Enable full ART optimizations with VDEX/ODEX
* Improve scrolling and Ram managment

# Changelog 29/12/'26:
* Inital A16 build
* Reconfigure sf properties
* Remove unused virtual framebuffer
* Disable memcg kernel and socket accounting
* Add Dolby Atmos
* Disable skia trace by default
* Update brightness configuration from stock
* Enable AOSP surfaceflinger
* Downscale task snapshots to 70%
* Disable high performance transitions
* Optimize activity open/close animations
* Use HintManager for HWUI
* Enable ADPF CPU hints for improved UI performance
