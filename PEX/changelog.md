# Changelog

## PixelExtended_cepheus-12.1-20220801-1603-UNOFFICIAL

*Clean flash recommended

### Device Side changes: 
  - Added 195Mhz and 810Mhz GPU Clock for UC and OC
  - Fixed DC Dimming after switched to SOVIET+ Kernel 
  - Fixed Dirac (Kanged from Evolution-X cepheus device trees)
  - Forced Disabled IORAP and ZRAM Writeback to fix random freeze issue. 
  - Refactor Overlay (Kanged from Evolution-X cepheus device trees)
  - Uses Private AVB Keys instead of public testkey
  - Uses Xiaomi Global fingerprint (V12.5.1.0.RFAMIXM fingerprint)
  - Switched to MGC Gcam instead of stock cam 
  - Switched to SOVIET STAR kernel (Thanks to Niviann bring back SOVIET for Mi 9 and credit to @NATO66613)

### ROM Side changes:
  V4.7 Summer Month!
  - Merged July Security Patch and synced with latest Pe
  - Add Applock
  - Add vibration patterns from OOS
  - Allow disabling QS battery estimates
  - allow disable of screenshot shutter sound
  - Fix toggling screen off FOD
  - Add QS Transparency level
  - Add Less boring heads up option
  - Make colored Statusbar Icons optional
  - ... and other small improvement
  
## Known Issue 
  - Green tint on status bar when using black wallpaper (padding issue)
