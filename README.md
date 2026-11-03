<div align="center">

<a href="https://shortmy.site"><img src="./assets/hero.svg" width="100%" alt="ShortMy — Self-hosted URL-shortener SaaS"/></a>

<a href="https://shortmy.site"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2600&pause=900&color=38BDF8&center=true&vCenter=true&width=760&height=46&lines=Long+URL+in.+Short+link+out.;Per-link+analytics+with+GeoIP;Plans%2C+payments+and+affiliates;Webhooks+%C2%B7+bulk+CSV+%C2%B7+6+themes" alt="Long URL in. Short link out. · Per-link analytics with GeoIP · Plans, payments and affiliates · Webhooks · bulk CSV · 6 themes"/></a>

<p>
  <a href="https://shortmy.site"><img src="https://img.shields.io/badge/Live-shortmy.site-38bdf8?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Live site"/></a>
  <img src="https://img.shields.io/website?url=https%3A%2F%2Fshortmy.site&style=for-the-badge&label=status&up_message=online&down_message=offline" alt="Status"/>
  <img src="https://img.shields.io/badge/Source-Private-334155?style=for-the-badge&logo=github&logoColor=white" alt="Source private"/>
  <a href="https://ajendra.info"><img src="https://img.shields.io/badge/Built_by-Ajendra-f472b6?style=for-the-badge&logo=codeigniter&logoColor=white" alt="Built by Ajendra"/></a>
</p>

<p>
  <a href="#-overview"><b>Overview</b></a> &nbsp;•&nbsp;
  <a href="#-features"><b>Features</b></a> &nbsp;•&nbsp;
  <a href="#-tech-stack"><b>Tech</b></a> &nbsp;•&nbsp;
  <a href="#%EF%B8%8F-architecture"><b>Architecture</b></a> &nbsp;•&nbsp;
  <a href="#-source-code"><b>Source</b></a>
</p>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:38bdf8,50:818cf8,100:f472b6&height=3&section=header" width="100%" alt=""/>

## ✨ Overview

**ShortMy** ([shortmy.site](https://shortmy.site)) is a self-hosted PHP URL-shortener SaaS. Links support custom codes, passwords, expiry, click caps, UTM parameters and tags, with guest and signed-in shortening behind rate limits.

It ships with per-link analytics (device, browser, OS and country via GeoIP), Free/Pro/Business plans with many payment methods, an affiliate system with withdrawals, sub-admin permissions, six UI themes with light/dark modes, webhooks, bulk CSV import/export, SMTP, hardened security headers, CSRF protection and hashed API keys.

<div align="center">
  <a href="https://shortmy.site"><img src="https://ajendra.info/uploads/projects/shortmy-site.jpg" width="92%" alt="ShortMy screenshot"/></a>
  <br/><sub>🖥️ Live at <a href="https://shortmy.site"><b>shortmy.site</b></a></sub>
</div>

## 🚀 Features

<div align="center">
  <img src="./assets/features.svg" width="100%" alt="ShortMy feature highlights"/>
</div>

| Feature | What it does |
|:--|:--|
| **Smart links** | Custom codes, passwords, expiry, click caps, UTM and tags. |
| **Link analytics** | Device, browser, OS and country breakdowns via GeoIP. |
| **Plans + payments** | Free/Pro/Business with UPI, PayPal, Stripe, crypto and more. |
| **Affiliates** | Referral earnings with a full withdrawal workflow. |
| **Developer ready** | Hashed API keys, webhooks and bulk CSV import/export. |
| **Hardened** | CSRF protection, security headers, rate limits, sub-admins. |

## 🧰 Tech Stack

<div align="center">

<img src="https://img.shields.io/badge/PHP_8-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP 8"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
<img src="https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white" alt="SQLite"/>
<img src="https://img.shields.io/badge/Apache-D22128?style=for-the-badge&logo=apache&logoColor=white" alt="Apache"/>
<img src="https://img.shields.io/badge/Vanilla_JS-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white" alt="Vanilla JS"/>

</div>

## 🏗️ Architecture

```mermaid
flowchart LR
    U["Visitor"] -->|"shortmy.site/code"| R{{"Redirect engine"}}
    R -->|"checks: password, expiry, click cap"| T["Target URL"]
    R --> A[("Click analytics + GeoIP")]
    O["Link owner"] --> D["Dashboard / API / CSV"]
    D --> L[("Links DB")]
    D --> P["Plans + payments"] --> F["Affiliates + withdrawals"]
    L --> W["Webhooks"]
```

## 🔒 Source Code

> [!NOTE]
> This is a **showcase repository**. The production source code of **ShortMy** is private and is not published here.
> Want a walkthrough, a similar build for your business, or licensing? **[Get in touch →](https://ajendra.info/contact)**

## 👤 Author

<div align="center">

**Ajendra** — Full Stack Developer · Security Researcher · AI Engineer · Startup Advisor

<a href="https://ajendra.info"><img src="https://img.shields.io/badge/Website-ajendra.info-8b5cf6?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"/></a>
<a href="https://github.com/ajendras"><img src="https://img.shields.io/badge/GitHub-ajendras-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
<a href="https://www.instagram.com/me_ajendra/"><img src="https://img.shields.io/badge/Instagram-me__ajendra-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/></a>
<a href="mailto:contact@ajendra.info"><img src="https://img.shields.io/badge/Email-contact%40ajendra.info-ec4899?style=for-the-badge&logo=maildotru&logoColor=white" alt="Email"/></a>

<sub>⭐ If you like this project, star the repo — and check out my other work on <a href="https://ajendra.info/projects">ajendra.info/projects</a>.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:04091a,50:38bdf8,100:f472b6&height=120&section=footer" width="100%" alt=""/>

</div>
