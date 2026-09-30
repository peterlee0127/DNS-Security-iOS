---
title: How to Enable DNS Security
description: Step-by-step guide to turn on encrypted DNS over HTTPS or DNS over TLS with DNS Security on iPhone, iPad and Mac, plus troubleshooting tips.
eyebrow: Setup guide
lead: Turn on encrypted DNS over HTTPS or DNS over TLS on your iPhone, iPad or Mac in under a minute.
---

## iPhone and iPad

1. Open **DNS Security**.
2. Choose a DNS profile in the **Config** tab.
3. Turn on DNS in the **Connect** tab.
4. When prompted, open the **Settings** app.
5. Go to **General › VPN & Network › DNS**.
6. Select **DNS Security**.

Return to DNS Security and check the **Status** tab. It shows the active DNS profile, the protocol in use and your network status.

## Mac

On macOS 13 Ventura or later:

1. Open DNS Security, choose a DNS profile and turn it on.
2. Open **System Settings**.
3. Go to **Network › VPN & Filters**.
4. Under **Filters & Proxies**, enable **DNS Security**.

On earlier macOS versions, open **System Preferences › Network**, choose **DNS Security** and make the service active.

## Switch DNS providers

Pick a different profile in the Config tab and DNS Security updates the system setting. DNS over HTTPS profiles end in **-DOH** and DNS over TLS profiles end in **-DOT**. Not sure which to use? Read [What is DNS over HTTPS and DNS over TLS?](dohdot.html)

With **DNS Security Pro** (or Lite with the Pro upgrade) you can also:

- add your own DoH or DoT server as a custom profile,
- turn encrypted DNS on or off automatically for specific Wi-Fi networks (SSIDs),
- switch profiles from Shortcuts or other apps with the URL scheme.

## Troubleshooting

**DNS is not active after I turned it on.**
iOS only uses the profile after you select it. Go to **Settings › General › VPN & Network › DNS** and make sure **DNS Security** is selected. You can open this guide again from the Connect or About screen in the app.

**Some websites do not load on a captive Wi-Fi network.**
Hotel and airport Wi-Fi login pages sometimes block encrypted DNS. Switch to **Automatic** DNS in Settings until you have signed in, then select DNS Security again. With Pro you can create a Wi-Fi SSID rule so this happens automatically.

**I use another VPN or DNS app.**
iOS uses one DNS setting at a time. If another app also manages DNS, choose which one to use under **General › VPN & Network › DNS**.

<div class="callout">
<p>Still stuck? <a href="https://github.com/peterlee0127/DNS-Security-iOS/issues">Open an issue on GitHub</a> and describe your device and iOS version.</p>
</div>
