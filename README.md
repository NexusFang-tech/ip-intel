# IP Intelligence Lookup

**Live:** [nexusfang-tech.github.io/ip-intel](https://nexusfang-tech.github.io/ip-intel)

Full IP intelligence dashboard — paste any IP address and get geolocation, ISP and ASN data, reverse DNS, BGP prefix and peer information, risk scoring with threat flags, an interactive world map with crosshair placement, and real-time DNS blacklist checks across 8 major DNSBLs.

## Features

- **Geolocation** — Country, region, city, coordinates with interactive map placement
- **Network intelligence** — ISP, organization, ASN, reverse DNS hostname
- **BGP data** — Prefix announcements, upstream peers, and routing information via BGPView API
- **Risk assessment** — Threat flags for Tor exit nodes, proxies, hosting providers, and known abusers
- **DNSBL checks** — Real-time queries against 8 major blacklists including Spamhaus (ZEN), Barracuda, SpamCop, SORBS, and more via Cloudflare DNS-over-HTTPS
- **Interactive map** — Crosshair marker on world map at the resolved coordinates
- **Vaporwave aesthetic** — Consistent with the NexusFang portfolio design language

## APIs Used

- [ipapi.co](https://ipapi.co) — Geolocation and network data
- [BGPView API](https://bgpview.docs.apiary.io) — BGP routing intelligence
- [Cloudflare DoH](https://developers.cloudflare.com/1.1.1.1/dns-over-https/) — DNSBL resolution

## Tech Stack

`Vanilla JS` · `ipapi.co` · `BGPView API` · `Cloudflare DoH` · `GitHub Pages`

All client-side. No backend required.

## Repo Description

> IP intelligence dashboard with geolocation, ASN/BGP data, reverse DNS, risk scoring, interactive map, and real-time DNSBL checks across 8 major blacklists. Client-side, zero dependencies.
