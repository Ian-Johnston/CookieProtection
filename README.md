# Cookie Protection

**Stops infostealer malware stealing your browser login & cookie files - Windows 10 & 11 (64-bit).**

By Ian Johnston Engineering Limited - [www.ianjohnston.com](https://www.ianjohnston.com/index.php/projects/cookieprotection)

## Requirements

- Windows 10 or 11, 64-bit
- .NET Framework 4.8 (already part of Windows 10 & 11)
- Administrator rights to install

## Installing

1. Download the zip from **Releases**, extract it and run `CookieProtection.msi`.
2. Open Cookie Protection from the desktop shortcut.
3. Click **Install Driver**, then **Turn Protection ON**.

Protection is **off after every Windows restart** - open the app and turn it on again. Closing the app doesn't stop protection, but nothing is logged until it's reopened.

To uninstall, use Windows Settings > Apps. The uninstaller turns protection off and removes the driver.

## Notes

- Some normal programs - Windows' SysMain, Microsoft Defender, and Opera's and Vivaldi's own helpers - read browser files now and then. They're blocked harmlessly and shown as **ℹ Normal**, with no pop-up.
- Not a replacement for antivirus.

Full details, the technical side and how it's been tested: [ianjohnston.com - Cookie Protection](https://www.ianjohnston.com/index.php/projects/cookieprotection)

## Discuss

Questions, suggestions and bug reports are welcome on the [EEVBlog forum](https://www.eevblog.com/forum/security/cookie-protection-a-windows-kernel-driver-that-blocks-cookie-theft/) or via the [contact page](https://www.ianjohnston.com/index.php/contact).

## Licence

Free for **personal, non-commercial use only**. Use within businesses and organisations needs a separate commercial licence - please get in touch. See [LICENSE.txt](LICENSE.txt).

The source code is not published at this time.

Windows, Microsoft Edge, Google Chrome, Mozilla Firefox, Opera, Brave, Vivaldi and other product names are trademarks of their respective owners. Cookie Protection is not affiliated with or endorsed by any of them.
