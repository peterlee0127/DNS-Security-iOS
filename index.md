---
title: DNS Security for iOS
description: Private DNS with DNS over HTTPS and DNS over TLS on iPhone, iPad, and Mac.
---

<style>
.hero {
  text-align: center;
  padding: 36px 0 20px;
}
.hero-icons {
  display: flex;
  justify-content: center;
  gap: 18px;
  margin-bottom: 18px;
}
.hero-icons img {
  width: 96px;
  height: 96px;
  border-radius: 22px;
}
.hero h1 {
  margin-bottom: 10px;
}
.hero p {
  max-width: 760px;
  margin: 0 auto 18px;
  font-size: 1.1em;
}
.app-links {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 14px;
  margin: 20px 0;
}
.app-link {
  display: inline-block;
  padding: 12px 18px;
  border: 1px solid #5ad1d1;
  border-radius: 8px;
  color: #ffffff;
  text-decoration: none;
}
.feature-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 16px;
  margin: 24px 0;
}
.feature-card {
  border: 1px solid rgba(255, 255, 255, 0.18);
  border-radius: 8px;
  padding: 16px;
}
.feature-card h3 {
  margin-top: 0;
}
.screenshot-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(190px, 1fr));
  gap: 18px;
  margin: 24px 0;
}
.screenshot-grid figure {
  margin: 0;
}
.screenshot-grid img {
  width: 100%;
  border-radius: 18px;
  box-shadow: 0 12px 28px rgba(0, 0, 0, 0.35);
}
.screenshot-grid figcaption {
  margin-top: 8px;
  text-align: center;
  font-size: 0.9em;
}
</style>

<section class="hero">
  <div class="hero-icons">
    <img src="assets/icons/dns-security.png" alt="DNS Security icon">
    <img src="assets/icons/dns-security-pro.png" alt="DNS Security Pro icon">
  </div>
  <h1>DNS Security</h1>
  <p>Secure DNS for iOS and Mac with DNS over HTTPS and DNS over TLS. Keep DNS queries encrypted without routing all traffic through a VPN server.</p>
  <div class="app-links">
    <a class="app-link" href="https://apps.apple.com/us/app/id1537782072">Download DNS Security Lite</a>
    <a class="app-link" href="https://apps.apple.com/us/app/id1533938029">Download DNS Security Pro</a>
  </div>
</section>

## What DNS Security Does

DNS Security configures Apple's system DNS settings to use encrypted DNS resolvers. It protects DNS lookups while leaving the rest of your network traffic untouched.

## Features

<div class="feature-grid">
  <div class="feature-card">
    <h3>One-tap encrypted DNS</h3>
    <p>Enable DNS over HTTPS or DNS over TLS from the Connect tab and follow the system prompt to activate the DNS profile.</p>
  </div>
  <div class="feature-card">
    <h3>Built-in DNS profiles</h3>
    <p>Use trusted DNS providers such as Google, Cloudflare, and AdGuard, with Lite and Pro behavior clearly separated.</p>
  </div>
  <div class="feature-card">
    <h3>Custom DNS profiles</h3>
    <p>Create your own DoH or DoT profile with validation for DNS server addresses and server names.</p>
  </div>
  <div class="feature-card">
    <h3>Wi-Fi SSID rules</h3>
    <p>Choose where DNS should be enabled or disabled by matching Wi-Fi SSIDs.</p>
  </div>
  <div class="feature-card">
    <h3>DNS status check</h3>
    <p>Review the current DNS profile, protocol, proxy state, and network status from the Status screen.</p>
  </div>
  <div class="feature-card">
    <h3>Shortcuts support</h3>
    <p>Pro users can switch DNS profiles from Shortcuts or other apps with the custom URL scheme.</p>
  </div>
</div>

## Screenshots

<div class="screenshot-grid">
  <figure>
    <img src="assets/screenshots/01-secure-dns-one-tap.png" alt="DNS Security Connect screen">
    <figcaption>Secure DNS in one tap</figcaption>
  </figure>
  <figure>
    <img src="assets/screenshots/02-pro-included.png" alt="DNS Security Pro included screen">
    <figcaption>Pro included</figcaption>
  </figure>
  <figure>
    <img src="assets/screenshots/03-free-requires-pro-iap.png" alt="DNS Security Lite Pro upgrade screen">
    <figcaption>Lite upgrade path</figcaption>
  </figure>
  <figure>
    <img src="assets/screenshots/04-create-custom-dns-profiles.png" alt="DNS Security custom DNS profiles screen">
    <figcaption>Custom DNS profiles</figcaption>
  </figure>
  <figure>
    <img src="assets/screenshots/05-verify-dns-status.png" alt="DNS Security status screen">
    <figcaption>Verify DNS status</figcaption>
  </figure>
  <figure>
    <img src="assets/screenshots/06-create-custom-dns-profiles-need-pro.png" alt="DNS Security Pro-only custom DNS profile screen">
    <figcaption>Pro-only tools</figcaption>
  </figure>
</div>

## Lite and Pro

DNS Security Lite includes the core encrypted DNS workflow. Pro unlocks advanced controls such as custom DNS profiles, Wi-Fi SSID rules, and profile switching from Shortcuts or other apps.

DNS Security Pro is a separate paid app with Pro included from the start. DNS Security Lite can unlock Pro features with an in-app purchase.

## How to Enable

1. Open DNS Security and choose a DNS profile.
2. Enable the switch in the Connect tab.
3. Open iOS Settings.
4. Go to General - VPN & Network - DNS.
5. Select DNS Security.

On Mac, enable the DNS proxy in System Settings - Network - VPN & Filters - Filters & Proxies.

## Privacy

DNS Security only configures DNS resolution through the provider you choose. It does not route all traffic through an app server, and it does not collect your browsing data.

## Learn More

- [What is DNS over HTTPS/TLS?](dohdot)
- [Privacy Policy](policy)
