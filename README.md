# XBuil

**Integrated Construction Business Management Platform**

[繁體中文](README.zh-TW.md) · [User guide](USER_GUIDE.md) · [Architecture](ARCHITECTURE.md)

XBuil connects project management, field operations, workforce and payroll, contracts, invoicing and company finance in a bilingual web application. It is designed for construction company administrators, field workers and project owners.

[Live demo](https://xbuild-demo.vercel.app/) — public interactive preview. Fictional browser-local data only.

## Features

| Area | Scope |
|---|---|
| Projects | Project list, detail, schedule and progress workflows |
| Workforce | Today labor, project assignments, attendance and salary workflows |
| Commercial | Quotations, contracts, invoices and PDF views |
| Finance | Project and company financial views, monthly reports |
| Company | Members, business contacts, announcements and settings |
| Collaboration | Communication Hub, messages, forum and AI assistant interface (AI runtime not verified) |
| Experience | Traditional Chinese and English, responsive desktop/mobile layout |

## Technology

React 19, TypeScript 5.7, Vite 6, Tailwind CSS 4, React Router 7, i18next, Supabase JS 2, Chart.js, Leaflet, Vitest and Playwright. Node >=20.19.0.

## Demo access

Choose Admin, Worker or Owner using the one-click demo login. No registration is required. All identities and data are fictional.

## Documentation

[Portfolio](PORTFOLIO.md) · [Role workflows](ROLE_WORKFLOWS.md)

This repository contains public-facing documentation only. Application source code is private. The demo is not a certified production system; business logic, performance and hosted security validation remain separate.

## Release verification / 發布驗證

2026-11-26: the public demo was switched to the CI-passing release. Recorded local acceptance: 3,523 tests across 457 files; 42/42 mock browser E2E checks; production dependency audit reported zero known advisories at release time. Hosted runtime and cloud AI are not certified; development dependency advisories remain. Public browser role-by-role retesting is pending.
