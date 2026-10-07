<h1 align="center">Naman Singh</h1>

<p align="center">
  <b>Backend &amp; security engineering</b> · Agra, Uttar Pradesh, India
</p>

I'm a backend engineer with a habit of reading source looking for the auth bug.
Most of the work I'm proud of is unglamorous — tokens redacted out of logs,
injection paths closed, credentials pulled from source — because software should
survive a bad day, not just a demo. Open to internships, remote roles and
freelance work.

Now: prepping for placements — DSA, system design, and security write-ups.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/stats-dark.svg">
    <img src="assets/stats-light.svg" height="165" alt="GitHub stats">
  </picture>
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/top-langs-dark.svg">
    <img src="assets/top-langs-light.svg" height="165" alt="Top languages">
  </picture>
</p>

## What I build

- **[DeepScan](https://github.com/namann5/Ai_deepfake)** — tells you whether an
  image is AI-generated: Xception inference, EXIF camera/GPS forensics, weighted
  score fusion across a four-service Docker stack. I owned backend and testing.
  [Live](https://ai-deepfake-rouge.vercel.app) · `Node.js` `FastAPI` `PyTorch` `React` `MongoDB`
- **[AnimeVerse](https://github.com/namann5/Anime-muesuem)** — a museum you walk
  through instead of scroll: era timelines, a cinema, a 3D character gallery on
  React + Firebase. 85 commits. [Live](https://animeverse-mvp.vercel.app) · `React` `Firebase`
- **[Packet_analyzer](https://github.com/namann5/Packet_analyzer)** — a DPI
  engine in C++. Parses PCAP byte-by-byte and pulls the hostname out of TLS
  Client Hellos (HTTPS leaks SNI in plaintext before encryption starts), then
  blocks flows by IP/app/domain rule. Packets route reader → load balancer →
  fast path by consistent hash of the 5-tuple, so every packet of one
  connection always lands on the same thread. Live capture via libpcap,
  JSON rules + CLI, CI on Linux/macOS/Windows.
- **[namancraft](https://github.com/namann5/namancraft)** — Minecraft-style
  build mode that runs in the browser.

## What I patch

Auth tokens used to go straight into the console — and from there into Metro
logs, device logs and Sentry. From a [merged fix](https://github.com/SB2318/UltimateHealth/pull/2320):

```diff
- console.log('[Login] res.data.token:', res.data?.token);
+ console.log('[Login] res.data.token:', res.data?.token ? 'present' : 'absent');
```

The log still tells you the token arrived; it just doesn't print the value.

Other things that made it through review, all merged:

- [Auth token never persisted in plaintext storage](https://github.com/SB2318/UltimateHealth/pull/2306)
- [Bypassable regex sanitizer replaced with an entity-aware tag sanitizer](https://github.com/SB2318/UltimateHealth/pull/2354)
- [Hardcoded Vultr API credential pulled out of source](https://github.com/SB2318/UltimateHealth/pull/2356)

## Open source

179 merged pull requests in repositories I don't own · 0 open —
[browse them yourself](https://github.com/search?q=author%3Anamann5+is%3Apr+is%3Amerged&type=pullrequests).

## Contact

<p align="center">
  <a href="https://www.linkedin.com/in/naman-singh-513260299"><img src="https://img.shields.io/badge/LinkedIn-namann5-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:naman.2002.as@gmail.com"><img src="https://img.shields.io/badge/Gmail-naman.2002.as%40gmail.com-D93025?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>
  <a href="https://noctratech.me"><img src="https://img.shields.io/badge/noctratech.me-000000?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"></a>
  <a href="https://leetcode.com/namann5"><img src="https://img.shields.io/badge/LeetCode-namann5-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" alt="LeetCode"></a>
</p>
