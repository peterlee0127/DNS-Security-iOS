---
title: What is DNS over HTTPS and DNS over TLS?
description: Learn how DNS over HTTPS (DoH) and DNS over TLS (DoT) encrypt DNS queries to protect your privacy, how they differ, and how to use them on iPhone, iPad and Mac.
eyebrow: Learn
lead: Encrypted DNS keeps the websites you visit from being exposed or tampered with on the network. Here is how DoH and DoT work.
---

## Why DNS needs encryption

Before your device can connect to a website or app server, it asks a **DNS resolver** to translate a name like `example.com` into an IP address. Traditional DNS sends these questions and answers in plain text over port 53.

That means anyone between you and the resolver, such as a public Wi-Fi operator or an internet provider, can:

- **see** every domain you look up, and
- **change** the answers to send you to a different server (DNS spoofing).

Encrypted DNS protocols solve this by wrapping DNS traffic in the same kind of encryption that protects websites.

## DNS over HTTPS (DoH)

**DNS over HTTPS** sends DNS queries inside regular HTTPS requests to a resolver URL such as `https://cloudflare-dns.com/dns-query`. It is defined in [RFC 8484](https://www.rfc-editor.org/rfc/rfc8484).

Because DoH uses port 443, like all other secure web traffic, it blends in with normal browsing and works on most networks.

## DNS over TLS (DoT)

**DNS over TLS** sends DNS queries over a dedicated, encrypted TLS connection to a resolver hostname such as `dns.google`. It is defined in [RFC 7858](https://www.rfc-editor.org/rfc/rfc7858).

DoT uses its own port, 853, which makes encrypted DNS easy to identify and manage on a network.

## DoH vs DoT at a glance

<div class="table-wrap" markdown="1">

| | DNS over HTTPS | DNS over TLS |
|---|---|---|
| Encryption | TLS via HTTPS | TLS |
| Port | 443 | 853 |
| Server setting | URL, e.g. `https://dns.google/dns-query` | Hostname, e.g. `dns.google` |
| Looks like | Normal web traffic | Dedicated DNS traffic |
| Best for | Networks that block uncommon ports | Clean separation of DNS traffic |

</div>

Both protocols give you the same core protection: nobody on the network can read or alter your DNS lookups. If one does not work on a particular network, try the other.

## Use DoH and DoT on iPhone, iPad and Mac

Since iOS 14 and macOS 11, Apple devices support encrypted DNS system-wide. [DNS Security](/) sets this up for you with profiles for trusted providers such as Cloudflare, Google Public DNS, AdGuard DNS and Quad9, so every app on your device benefits without a VPN.

[See how to enable DNS Security →](tutorial.html)
