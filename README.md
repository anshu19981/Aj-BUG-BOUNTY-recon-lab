# ⚔️ AJ Recon Lab – Full Bug Bounty Arsenal v3

[![Vibe](https://img.shields.io/badge/Vibe-Cyberpunk-00ff41.svg?style=flat-square)](#)
[![Security](https://img.shields.io/badge/Testing-Authorized--Only-00e5ff.svg?style=flat-square)](#)
[![Version](https://img.shields.io/badge/Version-3.0--Stable-bf5fff.svg?style=flat-square)](#)

**AJ Recon Lab v3** is a fully interactive, offline-first, client-side dynamic Bug Bounty Web Application and Command Cheatsheet Arsenal. It is specifically designed to streamline the workflows of advanced penetration testers, OSCP researchers, and bug bounty hunters. Despite being a single-file standalone HTML layout, it is packed with enterprise-grade utilities and exclusive automation generation scripts.

It now features a **Cyber Hacker Anime Animated Assistant Widget** and a real-time **Matrix Digital Rain Canvas Layer** integrated alongside dynamic cyberpunk theme options, maintaining uncompromised readability with a premium hacker aesthetic.

---

## 🚀 Key Interface Features

- **🌐 Protocol Auto-Stripper Input:** Entering `https://`, `http://`, or trailing slashes (`/`) in the target field automatically cleans them up on the back-end to extract the pure base domain.
- **🔍 Global Arsenal Live Filtering Engine:** A dynamic search engine that indexes metadata tags, command structures, tool names, and section headers in real-time. A search code badge indicates how many sections match the filter.
- **⬇️ Direct `.sh` Shell Script Exporter:** Generate a custom monolithic automation bash script (`recon_target.sh`) with domain-specific variable bindings and download it to your local system with a single click.
- **📋 Section-Wise Monolithic Copying:** The 'Copy All' feature copies all commands in a module into a single structural buffer stack, utilizing dynamic text substitution (target domain parameters mapping).
- **☀️/🌙 Adaptive Theme Controller:** Custom light and dark modules. Clicking the light theme automatically fades and desaturates the cyber background, ensuring smooth research in clear daylight environments.

---

## 🗺️ Deep Tab Architecture & Feature Mapping

### 1. ⚔️ The Recon & Exploitation Arsenal (20 Core Sections)
Each section contains dedicated real-world tactical objectives, tool strings, and sequential execution logs:

1. **Passive Recon & OSINT:** `crt.sh`, `subfinder`, `amass`, `theHarvester`, Shodan hostname search tracking, and historical URL dumps using `waybackurls` & `gau`.
2. **Active Subdomain Enumeration:** High-performance multi-threaded resolution setups containing `puredns`, `massdns`, `dnsx` CNAME workflows, and `alterx` permutation rules.
3. **ASN, IP & Infrastructure Discovery:** Mapping IP ranges utilizing `asnmap`, ultra-fast pipeline port scanning using `masscan`, and server banner grabbing using `httpx`.
4. **Live Hosts & Visual Recon:** Screenshots automation deployment using `gowitness` and `aquatone` alongside high-value visual keyword filtering (`admin`, `jenkins`, `grafana`).
5. **URL & Endpoint Discovery:** Recursive multi-level crawling sequences using `katana`, `gospider`, JS scraping loops, and deep target endpoint parsers like `LinkFinder` & `SecretFinder`.
6. **Parameter & Endpoint Fuzzing:** Automated parameter fuzzing with `arjun` alongside directory brute-forcing configurations via `ffuf` & `feroxbuster`.
7. **Vulnerability Scanning:** Fast mass vulnerability evaluations using targeted `nuclei` template severities, `nikto` audits, and SSL context verification using `testssl.sh`.
8. **Subdomain Takeover Hunting:** CNAME architecture extraction filters mapped against dangerous cloud endpoints (S3, GitHub Pages, Heroku) with `subjack`.
9. **Cloud Misconfiguration Auditing:** Resource discovery engines across AWS, GCS, and Azure deployments using `cloud_enum`, `s3scanner`, and direct unauthenticated storage wrappers.
10. **Core Web Vulnerabilities Pipeline:** Deep logic payload sequences for testing advanced SSRF (Metadata vectors), SSTI polyglots, LFI path traversals, and Host Header Cache Poisoning.
11. **GraphQL Security Testing:** Introspection testing strings, rate-limiting query batching bypass sequences, and alias object IDOR testing.
12. **CORS & CSP Misconfigurations:** Cross-Origin Resource Sharing evaluation wrappers verifying arbitrary, null, and post-domain reflection anomalies.
13. **HTTP Request Smuggling:** Smuggling sequences targeting dual-server infrastructure setups (`CL.TE`, `TE.CL`, `TE.TE` obfuscation, and modern `H2.CL` HTTP/2 downgrades).
14. **API Security Deep Dive:** Mapping OpenAPI specifications, version enumeration (v1 vs v2 regressions), BOLA/IDOR identification, and Mass Assignment fields injections.
15. **API Rate Limit Testing:** X-Forwarded-For IP address header spoofing rotators, MFA/OTP code brute-forcing modules, and parallel Turbo-Intruder single-packet race tracks.
16. **Auth & Session Testing:** Password reset host header injections, OAuth state-parameter CSRF account-linking checks, and JWT `alg:none` crypto signing attacks.
17. **Business Logic & Race Conditions:** Parallelized quantity modifications, payment step flow bypass configurations, and hidden multi-extension file upload workflows.
18. **Recon Automation & Monitoring:** Continuous asset monitoring frameworks relying on `anew` filtering layers, daily dynamic cron jobs, and JS file hash modification tracking.
19. **One-Liners & Hidden Gems:** Instant critical validation blocks including `.git` repository structural exposure verification (`git-dumper`) and automated Favicon MMH3 Shodan mapping.
20. **🕷️ CVE Hunting & 0-Day Discovery (2026 Edition):** Advanced static rule scanning using `semgrep`, semantic dependency flow mapping via `CodeQL`, Local LLM code reviews automation templates using `ollama` endpoints, and pipeline execution workflow injections targeting GitHub Actions rules.

### 🔎 2. Google Dorks Tab
An automated framework that compiles precise standard intelligence queries immediately upon domain entry:
- **Subdomain Discovery Dorks:** `site:*.target.com -www` to strip core stacks.
- **Sensitive Files Exposure Dorks:** High-impact extensions audits (`ext:env`, `ext:log`, `ext:sql`, `ext:bak`).
- **API & Docs Leaks:** Swagger, GraphQL endpoint directories, and public OpenAPI structures.
- **Cloud Infrastructure Trackers:** Open S3 buckets references, Azure storage dumps, and public Pastebin/GitHub code leaks filters.

### 💣 3. Payloads Tab
A specialized bypass payloads index designed to clear multiple security contexts and modern WAF rules layers:
- **XSS Focus:** SVG onload vectors, IMG onerror bypasses, and specialized cross-context Polyglot payloads.
- **SQLi Focus:** Multi-engine error extractions, boolean time-based blind constructs, and NoSQL operator injections (`$gt`, `$ne`).
- **SSRF & LFI Bypasses:** IPv6 mapped addresses, decimal notations, dotdotslash variations (`....//`), and advanced PHP wrappers filter streams.
- **Advanced Vectors:** SSTI detection blocks, XML External Entity (XXE) data leaks vectors, and request smuggling raw templates.

### 🌐 4. Wildcard Scope Tab
A dedicated asset pipeline designed specifically for massive scopes (`*.example.com`) in Bugcrowd / HackerOne enterprise targets:
- Massive multi-source subdomains aggregation pipelines.
- Wildcard DNS loop identification logic using `dig` comparisons before active DNS brute-forcing.
- Mass probing with metadata extraction engines.
- Continuous cron scheduling mechanics with integration protocols targeting messaging alerts (`notify`).

---

## 🛠️ Installation & Setup

Since this is built on a pure vanilla stack architecture, there is no need for a heavy setup, Docker containers, or server requirements.

1. Clone the repository or directly download the HTML source:
   ```bash
   git clone https://github.com/yourusername/aj-recon-lab.git
   cd aj-recon-lab
   ```
2. Open the `aj-recon-lab-v3.html` file in any modern web browser (Chrome, Firefox, Brave, Safari):
   ```bash
   # Linux / macOS
   xdg-open aj-recon-lab-v3.html || open aj-recon-lab-v3.html
   ```
3. Alternatively, you can deploy it via **GitHub Pages** for single-click hosting suitable for private intranets or local team environments.

---

## 🎨 Tech Stack & Visual Engineering
- **Markup & Layout:** Clean Semantic HTML5 structure with specialized modular container groupings.
- **Styling Architecture:** Responsive CSS3 Grid & Flexbox engines tailored specifically to ensure smooth layouts across wide monitors and mobile interfaces.
- **Animation Framework:** Dynamic `@keyframes` engines handling custom properties interpolation for floating items, aura pulses, lightning strokes, and visual transformation glows.
- **Canvas Engine:** HTML5 Canvas layer rendering continuous Matrix digital streams with dynamic variable manipulation based on window resize events.
- **Scripting Core:** Native Vanilla ECMAScript 6 handling deep DOM mutations, text streaming copies, dynamically mapped arrays parsing, and custom BLOB script assembly pipelines.

---

## ⚖️ Legal & Ethical Disclaimer

> **WARNING:** AJ Recon Lab v3 tools and commands are created for educational purposes, authorized penetration testing, and legitimate Bug Bounty programs only. Testing targets without explicit prior written authorization is strictly illegal and violates global cyber security laws. The developer assumes no liability and is not responsible for any misuse or damage caused by this application. Use responsibly. Happy hunting. 🐛
