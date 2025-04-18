# Changelog - April 06, 2025:
## Source:
- Merge March Security patch (doesn't include QPR2)
- Fix keyboard issues with parallel space
- Only show battery shield on default icon
- Fix empty version in DerpFest recovery Info header
- Bluetooth: Fix crash on some devices
- sidebar: Add a shortcut to open sidebar settings
- sidebar: Add a settings toggle for predicted apps
- Don't block QS tiles in keyguard that's not secure i.e Swipe
- QSGradient: Import ShishuAmalgamationTheme resources from Bootleggers
- Fix potential race conditions with FlashlightStrength and Volume control QS tiles
- FlashlightStrengthTile: Update bg color only if flash strength control is supported
- ThemePicker: Add QS gradient dark theme restriction
- Updater: Update dependencies
- Hide ongoing action progress chip on lockscreen
- OnGoingActionProgressController: Few code improvements
- Import BT Slice intent resources from SettingsGoogle
- ChargingControl: Catch all setCharging*() exceptions
- ChargingControl: Prevent crash against very frequent power toggle
- ThemePicker: Add QS tiles gradient option
- QuickTap: Kotlin code style and minor improvements
- Support generating JSON for community builds
- Enhance script robustness and error handling for JSON generator
- Update Accord prebuilt
- Update some translations
- Implement Ongoing action progressbar chip
- Make Ongoing action progressbar chip toggleable in notification settings and fix it for notch devices like p9 series
- Implement burn-in protection for status/navbar
- ChargingControl: Rename msToUTCString to msToHMSString
- SettingLib: Show only the current network IP addresses
- DerpLauncher: Do not show recents shortcut for floating window in secondary user
- Updater: Add welcome message with instructions
- Bring back Island notification feature
- IslandView: Improve memory management, animations and gesture handling
- Buttons: Support volume up/down to mute
- Add preferred network qs tile and Music qs tile
- FlashlightStrengthTile: Play haptic effects as the brightness changes by ±1%
- Fix flashlight strength tile in secondary user
- VPN tile: Don't ask for user/pw on IKEv2/IPSec PSK and RSA
- Settings: Remove dashboard category title top margin
- ChargingControl: Format notification's target time according to locale
- QuickTap: Code improvements
- DerpLauncher: Update widget section

## Device:
- Configure refresh rate brightness thresholds

## Kernel:
* Added KSU-Next and susfs support. You can find this as a separate boot.img in the "KSU-Next Boot" folder. There is NO root by default
