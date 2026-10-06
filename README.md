[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=58A6FF&center=true&vCenter=true&width=600&lines=Backend+%26+AI-FULL-STACK+Engineer;Building+DeepScan%2C+NEXUS+%26+more;Open+to+internships+and+freelance+work)](https://git.io/typing-svg)

# Naman Singh

**Backend & Security Engineering** — Agra, Uttar Pradesh, India.
Open to internships, remote roles and freelance work.

I like the layer of software right after the "cool demo" stage — the part where you have to make it reliable, explainable, and usable by someone who isn't you.

**[Record](#naman-singh) · [Selected works](#selected-works) · [Register](#register) · [In preparation](#in-preparation) · [Summary](#summary) · [Correspondence](#correspondence)**

ARCHIVE / 002

## Provenance

**186 merged pull requests · 0 open · 13 external repositories.**
Verified against GitHub's public API, 6 October 2026 — [check the query yourself](https://github.com/search?q=author%3Anamann5+is%3Apr+is%3Amerged&type=pullrequests).

Trailing year: 297 pull-request contributions · 248 issue contributions · 1,786 contributions · 196 active days · peak 39 in one day.

ARCHIVE / 003

## Selected works

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/namann5/namann5/main/assets/fig-01-deepscan-blueprint.svg">
  <img src="https://raw.githubusercontent.com/namann5/namann5/main/assets/fig-01-deepscan-paper.svg" alt="Technical drawing of the DeepScan verification pipeline with numbered callouts: EXIF forensics, visual artifact analysis, weighted score aggregation." width="720" height="460">
</picture>

**Fig. 1 — DeepScan · AI-generated media verifier.**
Multi-signal pipeline that flags synthetic images by combining EXIF forensics with visual artifact analysis instead of trusting one black-box model.
Materials: JavaScript · Node.js · React. Condition: shipped.
[repo](https://github.com/namann5/Ai_deepfake) · [live](https://ai-deepfake-rouge.vercel.app)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/namann5/namann5/main/assets/fig-02-packet-analyzer-blueprint.svg">
  <img src="https://raw.githubusercontent.com/namann5/namann5/main/assets/fig-02-packet-analyzer-paper.svg" alt="Exploded technical drawing of the Packet analyzer deep packet inspection engine: ethernet frame, IP and TCP, HTTP headers, SNI extraction, block or allow decision, drawn before tuning." width="720" height="460">
</picture>

**Fig. 2 — Packet analyzer · deep packet inspection engine.**
A multi-threaded C++ engine with a documented packet-flow architecture, drawn and documented before being tuned.
Materials: C++ · 14 commits. Condition: in the archive.
[repo](https://github.com/namann5/Packet_analyzer)

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/namann5/namann5/main/assets/fig-03-animeverse-blueprint.svg">
  <img src="https://raw.githubusercontent.com/namann5/namann5/main/assets/fig-03-animeverse-paper.svg" alt="Schematic of the AnimeVerse request flow: browser to routes to data layer with AniList GraphQL, streaming API and Firebase, with numbered callouts." width="720" height="440">
</picture>

**Fig. 3 — AnimeVerse · anime catalogue platform.**
An anime discovery platform built to get hands-on with GraphQL end-to-end instead of reading about it — timeline, cinema rails, a 3D museum hall and an orbitable model gallery.
85 commits — the largest own-repo record in this archive.
Materials: React 18.3 · Vite · Express · Firebase. Condition: shipped.
[repo](https://github.com/namann5/Anime-muesuem) · [live](https://animeverse-mvp.vercel.app)

---

**Marginalia — annotations on documents I don't own.** Most of this record was written in other people's repositories: HELPDESK.AI **57** · MergeShip **30** · NyayaVanni **25** · spectrax_1 **21** · UltimateHealth **15** · SecuScan **12** · skillbridge **11** — 14 forks total, **171 of the 186** merged PRs. SecuScan specifically: an annotated copy of [utksh1/SecuScan](https://github.com/utksh1/SecuScan), not my project.

ARCHIVE / 004

## Register

Twelve merged remediations in repositories I don't own. † marks a critical the maintainers labelled as such in the merged PR title. Every row links to its PR.

| # | Correction | Reference |
|:--|:-----------|:----------|
| 01 † | API key exposed in client bundle → moved behind server proxy (HELPDESK.AI) | [#3274](https://github.com/riteshbonthalakoti/HELPDESK.AI/pull/3274) |
| 02 † | Tenant isolation bypass → cross-company data exposure (HELPDESK.AI) | [#3025](https://github.com/riteshbonthalakoti/HELPDESK.AI/pull/3025) |
| 03 † | Hardcoded AES encryption key, CWE-798 (HELPDESK.AI) | [#2485](https://github.com/riteshbonthalakoti/HELPDESK.AI/pull/2485) |
| 04 | Stored XSS via markdown → rehype-sanitize (HELPDESK.AI) | [#1994](https://github.com/riteshbonthalakoti/HELPDESK.AI/pull/1994) |
| 05 † | Hardcoded admin-email backdoor removed (HELPDESK.AI) | [#1508](https://github.com/riteshbonthalakoti/HELPDESK.AI/pull/1508) |
| 06 | Auth token removed from WebSocket URL (spectrax_1) | [#954](https://github.com/Somil450/spectrax_1/pull/954) |
| 07 | Prototype pollution via archive decompression (spectrax_1) | [#923](https://github.com/Somil450/spectrax_1/pull/923) |
| 08 | Regex sanitizer bypassed → entity-aware sanitizer (UltimateHealth) | [#2354](https://github.com/SB2318/UltimateHealth/pull/2354) |
| 09 | JWT access/refresh tokens redacted from login logs (UltimateHealth) | [#2320](https://github.com/SB2318/UltimateHealth/pull/2320) |
| 10 | Document search scoped by session — IDOR closed (NyayaVanni) | [#681](https://github.com/choudharyms/NyayaVanni/pull/681) |
| 11 | Open redirect: next parameter validated (MergeShip) | [#853](https://github.com/Coder-s-OG-s/MergeShip/pull/853) |
| 12 † | Sequential template injection, SSTI (SecuScan — upstream utksh1) | [#1632](https://github.com/utksh1/SecuScan/pull/1632) |

† 5 of 12. Every row links to the merged PR — nothing here is a summary without a source.

ARCHIVE / 005

## In preparation

**NEXUS** — criminal network intelligence workbench. *In progress — no public repo yet.*
This sheet stays blank until there's a record worth filing.

ARCHIVE / 006

## Summary

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/namann5/namann5/main/assets/tally-blueprint.svg">
  <img src="https://raw.githubusercontent.com/namann5/namann5/main/assets/tally-paper.svg" alt="Bar chart of merged pull requests per month, December 2025 to September 2026: 2, 1, 0, 1, 14, 32, 63, 49, 22, 2. Peak June 2026 with 63." width="720" height="340">
</picture>

Merged PRs per month: `Dec 2 · Jan 1 · Feb 0 · Mar 1 · Apr 14 · May 32 · Jun 63 · Jul 49 · Aug 22 · Sep 2` — peak June 2026, 63 merged. Series verified via GitHub search API.

<details>
<summary>Appendix — materials &amp; full repository record</summary>

**Materials** — GitHub languages API across my own repos, plus manifests:

JavaScript · TypeScript · Python · Java · C++ · HTML · CSS · Node.js · Express · React · Vite · Firebase · FastAPI · PyTorch · MongoDB (Mongoose) · Docker · GraphQL (AniList client) · Tailwind CSS · Three.js · Jest · CMake · Meson

**Own repositories (15):**

| Repository | Language |
|:-----------|:---------|
| Ai_Customer_Service | HTML |
| Ai_deepfake | JavaScript |
| Anime-muesuem | JavaScript |
| approveflow-content-approval | JavaScript |
| autonomous-driving-system-clean | Python |
| Backend-Assignment | JavaScript |
| Backend-Practical-38 | JavaScript |
| experiment3 | — |
| LeetCode | Java |
| namancraft | JavaScript |
| namann5 | — |
| namann5.github.io | — |
| Packet_analyzer | C++ |
| UpiWithoutInternet | Java |
| Weather-App | CSS |

**Contribution index** — all 186 merged PRs by target repository:

| Repository | Merged |
|:-----------|-------:|
| riteshbonthalakoti/HELPDESK.AI | 57 |
| Coder-s-OG-s/MergeShip | 30 |
| choudharyms/NyayaVanni | 25 |
| Somil450/spectrax_1 | 21 |
| SB2318/UltimateHealth | 15 |
| utksh1/SecuScan | 12 |
| singhanurag0317-bit/skillbridge | 11 |
| namann5/Anime-muesuem | 3 |
| ronisarkarexe/story-spark-ai | 2 |
| Team-NoxVeil/InterXAI | 2 |
| Arpita2919/Demo-git-project | 1 |
| Krishnx21/Weather | 1 |
| namann5/skillbridge | 1 |
| namann5/Ai_deepfake | 1 |
| gunjanghate/GitGenie | 1 |
| Starbird265/coheart-pulse-retention | 1 |
| namann5/NyayaVanni | 1 |
| namann5/HELPDESK.AI | 1 |

**Contribution calendar:** 1,786 contributions (GitHub calendar term) · 196 active days · 905 in the last 90 days · peak 39 in one day.

</details>

## Correspondence

[GitHub](https://github.com/namann5) · [LinkedIn](https://linkedin.com/in/naman-singh-513260299) · [email](mailto:naman.2002.as@gmail.com) · [noctratech.me](https://noctratech.me) · [LeetCode](https://leetcode.com/namann5)

If you're hiring for a backend/AI-ML role or need something built — deepfake detection, a chatbot, an internal tool — my inbox is open.