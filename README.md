# Horythia
**Horythia controls the boundaries between your apps and the system.**

**Automatically toggle system settings per app. Wi-Fi, Cellular Data, Brightness, Volume, Do Not Disturb, Location Spoofing, and more. No Respring required.**

## What is Horythia?
Horythia automatically changes system settings the moment you open a specified app, and restores them when you leave. Set it once per app and let Horythia do the rest.

The base tweak is called <a href="https://www.reddit.com/r/jailbreak/comments/d0z6u6/release_networkdisabler_control_your_network_when/" target="_blank">NetworkDisabler</a>. Remade at the request of a reddit user.

<p middle="center">
  <img width="30%" alt="Settings View" src="https://github.com/user-attachments/assets/ce0d72a2-4fed-49ed-9ca1-1534a8a8bb77" />
  <img width="30%" alt="Location Spoofing" src="https://github.com/user-attachments/assets/65f2da33-59a9-4c2d-8b57-fe8cf6f525e0" />
  <img width="30%" alt="Home Screen Settings View" src="https://github.com/user-attachments/assets/31b3c9cc-9584-4a97-85c1-2f084e077dd7" />
  <img  width="30%" alt="3D Touch Menu" src="https://github.com/user-attachments/assets/92735e1d-7249-432d-9295-431b82d93f12" />
</p>

## Key Features
You can freely combine and configure the following options per app:

- Wi-Fi: On / Off
- Cellular Data: On / Off
- Location Services: On / Off
- **Spoof Location**: Set custom coordinates per app. Select directly on the map (search/tap), save favorite spots, or enter Latitude/Longitude manually
- Airplane Mode: On
- Do Not Disturb: On
- Low Power Mode: On
- Bluetooth: On / Off
- VPN: On
- Disable Auto-Lock
- Disable Auto-Brightness
- Set Brightness: Custom level slider
- Set Volume: Custom level slider
- Disable Orientation Lock

Additional Features:
- Quick configuration menu via Home Screen icon long-press (Force Touch / Haptic Touch)
- Searchable app list with configured apps pinned to the top
- Export / Import settings, with per-app or global reset options
- Conflict prevention (automatically locks mutually exclusive toggles like Wi-Fi On/Off)
- Instant application without needing a Respring

## Requirements
- iOS 15.0 or later
- Rootless / Rootful / Roothide jailbreak environments (Roothide package is provided separately as Havoc does not support it directly)
- Dependencies: `mobilesubstrate` / `ElleKit`, `PreferenceLoader`
- Tested on: iOS 15.1 (Dopamine roothide) / iOS 15.4.1 (Dopamine) / iOS 16.5 (Dopamine) / iPadOS 17.5.1 (Dopamine) / iPadOS 18.6 (palera1n) / iOS 26.0.1 (Dopamine)

## Highlights
- **Set & Forget**: Optimal settings apply when you open an app and automatically revert when you close it.
- **App-Specific Control**: Tailor settings for each app individually rather than system-wide.
- **Quick Access**: Edit settings on the fly directly from the home screen quick action menu.
- **Safe Testing**: Easily backup and restore your entire setup.
- **17 Languages Supported**

## Supported Languages
English、日本語、简体中文、繁體中文、한국어、Español、Français、Deutsch、Italiano、Português (Brasil)、Русский、العربية、Türkçe、Bahasa Indonesia、ไทย、Tiếng Việt、Nederlands

## Refund Policy
If Horythia does not work on your device/iOS version and the issue cannot be resolved, please contact support within 3 days of purchase. Refunds will be processed through Havoc if troubleshooting fails. Please double-check compatibility before purchasing.

## Important Notes
- Horythia changes live system settings while the app is in the foreground and restores them upon exit. If SpringBoard restarts while a configured app is open, some settings may remain modified.
- **Location Spoofing** only overrides location data delivered to that specific app; system-wide location remains unchanged. Apps with advanced detection or server-side verification may still detect your real location.
- Target apps must be capable of loading tweak hooks. If you use tools like Choicy, ensure injection is allowed for Horythia.
- **Some apps and games prohibit location spoofing in their Terms of Service. Use at your own risk.**
- Please be aware that if there are any tweaks or apps that disguise your location information, the tweak may not function properly.
- Airplane Mode includes an option to keep Wi-Fi enabled.
- This uses a UIKit filter for location spoofing, but everything else works with SpringBoard.

## Privacy
Horythia does not collect or transmit any user data. Note the following:
- "Select on Map" utilizes Apple Maps service for rendering map views and location search.
- "Email Support" automatically drafts an email containing your device model, iOS version, UDID, and installed package list. You can review and edit all content before sending.

## Companion Add-on
An optional CCSupport add-on (to toggle Horythia On/Off from Control Center) requires CCSupport to be installed separately.

## Video
Watch Horythia in action: <a href="https://www.youtube.com/watch?v=NMXWyFqaAgQ" target="_blank">iOS Tweaks Horythia demonstration - YouTube</a>

## Support
Email: Accessible via in-tweak settings link or Havoc page / Bluesky: [@ichitaso.com](https://bsky.app/profile/ichitaso.com) / Discord: [https://discord.gg/FuDBaWryge](https://discord.gg/FuDBaWryge)

## Localizable
If you want to add or edit a language, please send a pull request.
