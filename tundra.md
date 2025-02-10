# Changelog - February 10, 2025:
## Source:
- Merged February security patch
- Implement Android 16 seekbars (https://m3.material.io/components/sliders/overview)
- Fix headline font being stuck to roboto in Security & Privacy settings
- LongSwipe: Add show volume panel action
- QSHeader: Fix memory leaks
- QuickTap: Many code improvements
- DerpLauncher: Improve restart logic
- device_config: Add values required for Speech Recognition
- textclassifier: Set manifests + needed options
- Add haptic feedback to auto brightness icon
- Add click actions to QS header elements
- Bring back animated volume icon in volume panel when playing media
- Prevent OOB when reinflating QS panel with notifications
- Code improvements for FlashlightStrengthTile
- Code improvements for VolumeControlTile
- Optimize connected battery level scanning
- Fix custom image provider for header image
- Settings: Bring back Custom Statusbar Signal & Wi-Fi icons
- GameSpace: Add game optimization settings
- GameSpace: Enhance in-game call handling
- GameSpace: Improve seekbars
- QuickTap: Improve haptic intensity preference behavior
- QuickTap: Import German translations

## Device:
- Override DerpFest's Flash camera with Moto Camera
- Added Lineage Health support (charging control)
- Increased screen recorder max framerate to 120 fps

## Kernel:
- Upstreamed the kernel to 5.4.289 with the latest LineageOS changes
- Added KSU-Next and susfs support. You can find this as a separate boot.img in the "KSU-Next Boot" folder. There is NO root by default
