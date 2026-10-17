# Hi, I'm Liujian Zhang (Alex) 👋
### Senior Automation Engineer & Data Extraction Specialist

[![Upwork Profile](https://img.shields.io/badge/Upwork-Available%20for%20Hire-14a800?style=for-the-badge&logo=upwork&logoColor=white)](https://www.upwork.com)
[![Python](https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Docker](https://img.shields.io/badge/Docker-Containerized-2496ED?style=for-the-badge&logo=docker&logoColor=white)](https://www.docker.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

I specialize in **resilient web scraping, private API reverse engineering, and turnkey automated data pipelines**. I solve complex anti-bot challenges (Cloudflare Turnstile, TLS JA4 fingerprinting, Akamai, Dynamic SPAs) and deliver clean, validated datasets packaged inside reproducible Docker containers.

---

### 🛠️ Core Technical Capabilities

* **Anti-Bot Resilience**: Bypass Cloudflare Turnstile, 403 Forbidden blockers, Akamai Bot Manager, and TLS JA4/HTTP2 fingerprint checks using browser virtualization (Patchright / Camoufox) and TLS-spoofed HTTP clients.
* **Turnkey Packaging**: Zero host pollution. All deliverables are pre-configured with `Dockerfile` and `docker-compose.yml` for single-command (`docker compose up`) execution.
* **API Reverse Engineering**: Deconstruct private web/mobile APIs, inspect network payloads, reverse HMAC/JWT request signing, and achieve 100x speedups over heavy browser automation.
* **Data Cleansing & Integrity**: Pydantic schema validation, multi-currency price parsing, UTF-8 BOM encoding for Excel compatibility, and automated export to CSV, JSON Lines, PostgreSQL, and SQLite.

---

### 🏆 Featured Showcase Repositories

| Repository | Focus Area | Key Technologies | Quick Demo |
| :--- | :--- | :--- | :--- |
| [**stealth-scraper-toolkit**](https://github.com/ziaochina/stealth-scraper-toolkit) | Anti-Bot Resilience & 403 Bypass | Python, TLS JA4, Turnstile, Residential Proxy | `docker compose up` |
| [**turnkey-docker-pipeline**](https://github.com/ziaochina/turnkey-docker-pipeline) | Production Container Scaffold | Docker, Pydantic, Healthchecks, UTF-8 CSV | 1-Minute Run |
| [**ecommerce-catalog-harvester**](https://github.com/ziaochina/ecommerce-catalog-harvester) | E-Commerce Scraping & Parsing | Shopify, WooCommerce, Variant Unwrapping | Sample CSV Included |
| [**private-api-reverse-harness**](https://github.com/ziaochina/private-api-reverse-harness) | API Reverse Engineering & Signing | Network Reverse, HMAC-SHA256, AST Cleanse | Mock API Tested |

---

### 💻 Tech Stack & Tooling

```text
Languages:     Python (Asyncio, Pydantic, Requests, Httpx), Rust (Core Protocols), JavaScript/Node.js
Automation:    Patchright, Camoufox (Firefox C++), Selenium, CDP (Chrome DevTools Protocol)
Networking:    TLS JA3/JA4 Spoofing, Residential & Mobile Proxy Mesh, Xray/WARP Gateway
Databases:     PostgreSQL, SQLite (WAL mode), Redis, Pandas
DevOps:        Docker, Docker Compose, Linux CLI, Git, GitHub Actions, Cron
```

---

### 🤝 How I Work with Clients

1. **Deterministic Pre-flight Probing**: I test target defenses before accepting any contract to ensure 100% feasibility.
2. **Free 20-Row Sample Data**: I provide verified sample data (`sample.csv`) upfront to confirm column schemas before billing.
3. **Turnkey Docker Deliverables**: You get production-ready code that runs in one command on your server or laptop.
4. **Strict Scope & Confidentiality**: Zero credential leaks, clean environment variable templates, and prompt delivery.

📫 **Let's Discuss Your Project**: Contact me directly on [Upwork](https://www.upwork.com) or submit an issue in any showcase repository.
