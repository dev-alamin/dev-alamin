# Al Amin — WordPress Engineer

**Building production-grade WordPress systems. Not themes. Not page builders. Engineered plugins, WooCommerce infrastructure, and server-managed deployments.**

📍 Khulna, Bangladesh &nbsp;·&nbsp; 🌐 [almn.me](https://almn.me) &nbsp;·&nbsp; 📧 hmalaminmb4@gmail.com &nbsp;·&nbsp; 💼 [LinkedIn](https://www.linkedin.com/in/contactalamin/)

---

## What I Build

I specialize in the backend engineering layer of WordPress — custom plugin architecture, WooCommerce business logic, REST API systems, and server-level infrastructure. I manage **20+ live production websites** on self-configured VPS environments (Ubuntu + Nginx), and I understand the full stack from DNS and Cloudflare edge rules down to PHP process management and database query optimization.

My work is production-grade: sanitized inputs, prepared SQL statements, proper nonce handling, capability checks, and WordPress Coding Standards throughout.

---

## Core Competencies

**WordPress Engineering**
- Custom plugin development with OOP PHP — service container pattern, hook-based architecture, single-responsibility classes
- WooCommerce extensions: custom pricing logic, checkout flow, cart manipulation, REST API endpoints, order lifecycle hooks
- Gutenberg block development and Full Site Editing (FSE) integration
- Custom Post Types, taxonomies, metadata modeling, and query optimization
- REST API design: custom endpoints, authentication, pagination, caching layers
- WP-CLI automation for deployments, data migrations, and maintenance tasks

**DevOps & Server Infrastructure**
- Managing 20+ websites on VPS (Ubuntu + Nginx) — zero shared hosting
- Cloudflare configuration: WAF rules, bot protection, caching behavior, page rules, Workers
- SSL/TLS management, DNS configuration, HTTP/2 optimization
- Nginx server block configuration, PHP-FPM tuning, OPcache setup
- DigitalOcean, Vultr, Cloudways, WP Engine, Pantheon deployments
- CI/CD pipelines with GitHub Actions for automated plugin deployments
- Network-level security: rate limiting, fail2ban, IP allowlisting, bad bot filtering at the edge

**Performance Engineering**
- Core Web Vitals optimization (LCP, CLS, INP)
- Object caching, transient API, full-page caching strategies
- Database query profiling with Query Monitor and slow query logs
- Asset optimization: lazy loading, critical CSS, script defer/async strategy
- CDN configuration and cache purge automation

**Security**
- Malware remediation and hacked site recovery (50+ sites)
- Hardening: file permissions, `wp-config.php` protection, xmlrpc disabling, login protection
- OAuth 2.0 implementation (Google API integration in EntryDashboard)
- Secure AJAX handlers, REST API authentication, nonce verification

**Frontend**
- JavaScript (ES6+), Alpine.js, React, jQuery
- Tailwind CSS, SCSS, Bootstrap
- Headless WordPress with Next.js and REST API / WPGraphQL

---

## Open Source Projects

### [EntryDashboard – Forms Entries Manager](https://wordpress.org/plugins/entries-manager/)
*Live on WordPress.org 40+ active installation*

A centralized form submission management system — a lightweight CRM built directly inside WordPress. Supports WPForms, Contact Form 7, and Elementor Forms.

**Technical highlights:**
- OAuth 2.0 Google Sheets integration (no API key exposure — uses a secure backend proxy)
- Action Scheduler-based async bulk export system
- Server-side pagination and global search with optimized `$wpdb` queries
- Alpine.js + Tailwind admin UI
- Full WordPress.org compliance: prefixed namespaces, `$wpdb->prepare()`, proper escaping, i18n-ready

---

### [ShopSpark – WooCommerce UX Plugin](https://github.com/dev-alamin/ShopSpark)
*In active development*

A modular WooCommerce enhancement plugin covering the full shopper journey — shop page, single product, cart, and checkout.

**Features in build:**
- AJAX Add to Cart, Quick View, floating side cart
- Variation display enhancements, quantity controls
- FOMO countdown timers, recently viewed products
- Delivery time picker at checkout
- Honeypot + reCAPTCHA on account pages

---

### [rtCamp / Login with Google](https://github.com/rtCamp/login-with-google)
*Open source contribution — enterprise-grade plugin used across production WordPress sites*

Contributed to rtCamp's official Google login plugin for WordPress. This plugin follows strict enterprise coding standards including PHPCS, unit testing, and WordPress VIP compatibility.

---

### [Read Little – WooCommerce Plugin](https://wordpress.org/plugins/read-little/)
*Live on WordPress.org*

Lightweight plugin to embed documents and images directly inside WooCommerce product pages.

---

## Client Work

| Project | Stack | Scope |
|---|---|---|
| [HayatiVape](https://hayativape.co.uk/) | WooCommerce, DigitalOcean, Nginx, Cloudflare | Full build + server infrastructure + SEO architecture |
| [VapeHub](https://vapehub.co.uk) | WooCommerce (~$500K/mo volume) | Performance optimization, checkout UX, Core Web Vitals |
| [LifeFriendSurance](https://lifefriendsurance.com) | WordPress, VPS | Full site recovery post-hack, VPS migration, SSL, hardening |

---

## Employment

**WordPress Developer — Fjord Media** *(Feb 2025 – Present, Remote / Norway)*
Custom Elementor widgets, WooCommerce plugins with complex pricing logic, AJAX performance optimization, managed recovery of 50+ hacked sites.

**WordPress Developer — Mediavest AS** *(Jan 2023 – Jan 2025, Remote / Norway)*
WooCommerce variation UX with Alpine.js + REST API, custom plugin development, site migrations and hosting-level infrastructure management.

**WordPress Developer — BluBird Interactive Ltd** *(Nov 2021 – Jan 2023, Dhaka)*
Custom plugin and theme development with PHP OOP, CPTs, REST API, WooCommerce extensions, site recovery and migrations.

---

## Infrastructure I Run Daily

```
20+ production sites · Ubuntu 22.04 LTS · Nginx · PHP-FPM · MySQL
Cloudflare (WAF + bot rules + caching) · GitHub Actions CI/CD
DigitalOcean / Vultr VPS · SSL/TLS · fail2ban · OPcache
```

---

## Currently Studying

- PHPUnit testing for WordPress plugins
- WP_Mock for unit-testable hook-driven code
- Advanced DSA on [LeetCode](https://leetcode.com/u/dev-alamin/) — consistent daily practice

---

## Profiles

- 🔌 WordPress.org: [coderalamin](https://profiles.wordpress.org/coderalamin/)
- 🧠 LeetCode: [dev-alamin](https://leetcode.com/u/dev-alamin/)
- 🎨 ThemeForest: [Shalik Theme](https://themeforest.net/user/shalik-theme/portfolio)
- 💼 LinkedIn: [contactalamin](https://www.linkedin.com/in/contactalamin/)
- 🌐 Portfolio: [almn.me](https://almn.me)
