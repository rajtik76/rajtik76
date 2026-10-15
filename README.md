# Vladislav Rajtmajer

Senior PHP / Laravel engineer with 12+ years of building backends: REST and
user-facing API design, PostgreSQL, queues, and the boring reliability work
that keeps APIs predictable. On the frontend I work in Livewire and Vue.js.

Before the web I spent a decade in embedded and IoT, writing firmware in C for
Atmel AVR and PIC. That is where I learned to keep data contracts strict and to
treat edge cases as the normal case.

I use AI every day, in the products and in the editor, and I know where it
breaks. So the model gets a strict schema and deterministic tools, and the
tests, not the model, say when the work is done.

Available for remote contract work across the EU. Czech OSVC, B2B only, part-time welcome.

## Products I build and run

- **[captchaapi.eu](https://captchaapi.eu)** - GDPR-compliant proof-of-work CAPTCHA, EU-hosted
- **[billify.cz](https://billify.cz)** - invoicing for Czech businesses; an LLM reads received PDF invoices into the monthly VAT return, with the exchange rate from a tool and a human confirming every row
- **[laravel-blog.cz](https://laravel-blog.cz)** - writing about Laravel and AI-assisted development

## Open source

- **[exile2exile](https://github.com/rajtik76/exile2exile)** - a free Path of Exile 2 companion with a build planner, passive tree, loot filter generator and shareable builds. Laravel 13 on PHP 8.4 with React, Inertia and TypeScript, PostgreSQL and Redis, automated game-data releases and CI contract tests. Running at [poe.rajtik.com](https://poe.rajtik.com)
- **[captchaapi/laravel](https://github.com/captchaapi/laravel)** - official Laravel SDK for captchaapi.eu, with native Livewire support
- **[poe2-toolkit](https://github.com/rajtik76/poe2-toolkit)** - eight MIT-licensed TypeScript packages on npm that exile2exile is built on: GGPK extraction for game data, a headless passive-tree geometry engine and a WebGL renderer
- **[weather-station](https://github.com/rajtik76/weather-station)** - a balcony weather station that corrects its own sun-heated radiation shield. My own ESP32 firmware in C++ (I2C / I2S sensors, rain heard in the microphone spectrum, KiCad schematics), a Laravel API and dashboard, and a regression model calibrated against the Czech Hydrometeorological Institute (ČHMÚ) station Plzeň-Mikulka that subtracts solar heating from light and sun position. It goes live only after beating the raw sensor on held-out days. Versioned wire protocol, idempotent ingest. Running at [weather.rajtik.com](https://weather.rajtik.com)
- **[pis-cesky](https://github.com/rajtik76/pis-cesky)** - a Claude Code plugin that teaches AI to write Czech that does not read like a translation. Rules derived from human-written Czech instead of a phrase blacklist, and a proofreading agent that never sees the brief

Published on Packagist, WordPress.org and npm.

## Stack

**Backend** - PHP, Laravel, REST API design, PostgreSQL, MySQL, Redis, queues  
**Frontend** - Livewire, Vue.js, Inertia, React, TypeScript  
**Practice** - Pest, PHPUnit, PHPStan, Docker, CI/CD, SCRUM  
**AI** - LLM integration (Claude, laravel/ai, structured output, tool use), Claude Code  
**Also** - embedded C (Atmel AVR, PIC, ESP32), IoT telemetry

## Contact

[rajtik.com](https://rajtik.com) - [CV](https://rajtik.com/cv.pdf) - [LinkedIn](https://www.linkedin.com/in/vladislavrajtmajer/) - [X](https://x.com/VRajtmajer)

Pilsen, Czech Republic (CET). Reachable 10:00-19:00.

Open-source work is pinned below.
