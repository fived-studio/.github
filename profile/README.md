<div align="center">

# FiveD Studio

### `Five engineers. One studio. Software that ships.`

A small product studio building real software with real users —  
from Saigon, with caffeine.

### → [**fived-studio.github.io**](https://fived-studio.github.io)

[![Site](https://img.shields.io/badge/site-fived--studio.github.io-00d992?style=flat-square&labelColor=050507&logo=githubpages&logoColor=00d992)](https://fived-studio.github.io)
[![Org](https://img.shields.io/badge/github-fived--studio-f2f2f2?style=flat-square&labelColor=050507&logo=github)](https://github.com/fived-studio)
[![Team](https://img.shields.io/badge/team-5%20engineers-00d992?style=flat-square&labelColor=050507)](#-the-team)
[![Origin](https://img.shields.io/badge/origin-UIT%20VNU--HCM-b8b3b0?style=flat-square&labelColor=050507)](https://www.uit.edu.vn/)
[![Status](https://img.shields.io/badge/status-shipping-00d992?style=flat-square&labelColor=050507)](#-currently-building)
[![Code of Conduct](https://img.shields.io/badge/code%20of%20conduct-2.1-b8b3b0?style=flat-square&labelColor=050507)](../CODE_OF_CONDUCT.md)

</div>

---

```bash
$ git log --author="@fived-studio" --since="30 days"
# 5 engineers · 4 products · 0 days off · live at fived-studio.github.io

$ curl -s https://api.fived.studio/v1/totals?days=30
# live engineering pulse — every push, PR, review across the studio
```

---

## ⚡ About

We're **FiveD Studio** — a five-person engineering crew that grew up together in the **Software Engineering class of 2022** at **UIT, VNU-HCM**.

By day we're software & product engineers at **enterprise SaaS companies and tech corps**, working on platforms used by millions. By night and weekend, we ship our own products here.

This GitHub org is where those products live: real codebases, real users, real lessons. No homework, no abandoned demos.

> **Why a studio?** Because the best products come from a small group that ships together over years — not solo side projects, not 100-person factories.

**→ Visit [fived-studio.github.io](https://fived-studio.github.io)** for the full story — products, principles, member pages, and live engineering activity.

---

## ⚡ Operating principles

```
01  ship early, iterate honestly      → real users beat hypothetical ones
02  boring tech where it counts       → postgres, queues, good tests
03  product engineering               → end-to-end ownership, no handoffs
04  craft is the point                → pixels, latency, error messages
05  default to writing                → decisions live in PRs, not heads
```

---

## ⚡ Currently building

| Product | What it does | Repo |
| --- | --- | --- |
| ☕ **Coffee Shop Management** | POS, inventory, and order workflow built for independent coffee shops. | [CoffeeShopManagement](https://github.com/fived-studio/CoffeeShopManagement) |
| 🧠 **Enigma** | AI-assisted dropshipping platform — list products, capture margin, no inventory. | [Enigma-Frontend](https://github.com/fived-studio/Enigma-Frontend) |
| ⚙️ **Enigma (Java)** | Java/Spring services powering Enigma's backend. | [Enigma-Java](https://github.com/fived-studio/Enigma-Java) |
| 🏝️ **Resort Management System** | Operations platform for resorts — guests, rooms, billing, admin. | [RMS-BE](https://github.com/fived-studio/ResortManagementSystem-BE) |
| 📊 **Repo Ranker** | Dashboard ranking our GitHub repos by 14-day traffic, clones, stars, and recent activity. | [repo-ranker](https://github.com/fived-studio/repo-ranker) |

> See everything we're up to on the [organization page →](https://github.com/orgs/fived-studio/repositories)

### 🛰️ FiveD Pulse — *now live*

Real-time engineering activity from every team member, aggregated across the
FiveD org and their personal repos. Every push, PR, review, and release on a
single public timeline at **[fived-studio.github.io/live →](https://fived-studio.github.io/live)**.

Backend is open source at [fived-studio/pulse](https://github.com/fived-studio/pulse) —
Bun + Hono + Postgres + Redis on Cloud Run, fan-out via Server-Sent Events.

```bash
$ curl -N https://api.fived.studio/v1/stream/events
# SSE stream — every git event from the studio, in flight
```

---

## ⚡ Stack we reach for

| Layer | Tools |
| --- | --- |
| **Frontend** | TypeScript · React · Next.js · React Native · Tailwind |
| **Backend** | Node.js · NestJS · Java / Spring Boot · Python · Go |
| **Data** | PostgreSQL · MongoDB · Redis · Kafka |
| **Infra** | Docker · Kubernetes · AWS · GCP · Terraform · GitHub Actions |
| **Design** | Figma · Storybook |

The right tool for the job. The table above is what we keep reaching for.

---

## ⚡ The team

Now scattered across enterprise SaaS, product companies, and platform teams — still shipping together here. Each member has a profile page on our site.

| # | Name | Role | GitHub | Profile |
| :-: | :-- | :-- | :-- | :-- |
| 1 | Huỳnh Gia Bảo       | Fullstack Engineer                      | [![hgbaooo](https://img.shields.io/badge/hgbaooo-101010?style=flat-square&labelColor=050507&logo=github&logoColor=00d992)](https://github.com/hgbaooo)             | [/m/hgbaooo →](https://fived-studio.github.io/m/hgbaooo)         |
| 2 | Nguyễn Quốc Thắng   | Frontend Engineer · UI/UX               | [![nquynqthanq](https://img.shields.io/badge/nquynqthanq-101010?style=flat-square&labelColor=050507&logo=github&logoColor=00d992)](https://github.com/nquynqthanq) | [/m/nquynqthanq →](https://fived-studio.github.io/m/nquynqthanq) |
| 3 | Nguyễn Thành Tài    | Frontend Engineer · UI/UX               | [![thvnhtai](https://img.shields.io/badge/thvnhtai-101010?style=flat-square&labelColor=050507&logo=github&logoColor=00d992)](https://github.com/thvnhtai)           | [/m/thvnhtai →](https://fived-studio.github.io/m/thvnhtai)       |
| 4 | Trương Lê Vĩnh Phúc | Product Engineer · DevOps · Fullstack   | [![sloweyyy](https://img.shields.io/badge/sloweyyy-101010?style=flat-square&labelColor=050507&logo=github&logoColor=00d992)](https://github.com/sloweyyy)           | [/m/sloweyyy →](https://fived-studio.github.io/m/sloweyyy)       |
| 5 | Trần Tuệ Tánh       | Fullstack Engineer                      | [![TrTueTah](https://img.shields.io/badge/TrTueTah-101010?style=flat-square&labelColor=050507&logo=github&logoColor=00d992)](https://github.com/TrTueTah)           | [/m/TrTueTah →](https://fived-studio.github.io/m/TrTueTah)       |

---

## ⚡ Working with us

Whether you want to **report a bug**, **suggest a feature**, **contribute code**, or **partner up** — there's a path:

- 🐛 **Found a bug?** → open an issue with the bug template on the affected repo
- 💡 **Have an idea?** → open a feature request, lead with the user problem
- 🛠 **Want to contribute?** → read [`CONTRIBUTING.md`](../CONTRIBUTING.md)
- 🔒 **Found a security issue?** → see [`SECURITY.md`](../SECURITY.md), please don't open a public issue
- 🤝 **Partnership / hiring?** → `hello@fived.studio`

We hold ourselves and our community to a [Code of Conduct](../CODE_OF_CONDUCT.md).

---

<div align="center">

`built with caffeine, late nights, and pull requests in Ho Chi Minh City`

<sub>if something we built helped you ship — let us know. that's the whole point.</sub>

</div>
