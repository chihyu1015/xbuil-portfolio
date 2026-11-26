# XBuil 整合式營建工程與企業管理平台

[English](README.md) · [使用指南](USER_GUIDE.md) · [系統架構](ARCHITECTURE.md)

XBuil 將專案管理、工程現場、人員與薪資、報價合約、請款及公司財務整合於同一套繁體中文與英文網頁應用程式，服務管理員、現場工人與業主。

[公開線上展示](https://xbuild-demo.vercel.app/)：使用虛構且獨立儲存在瀏覽器的資料。

## 核心功能

| 模組 | 功能範圍 |
|---|---|
| 工程管理 | 專案列表、詳情、工期及進度流程 |
| 人員與薪資 | 今日出工、工程指派、出勤與薪資流程 |
| 商務管理 | 報價、合約、請款與 PDF 檢視 |
| 財務管理 | 工程及公司財務、月報 |
| 公司管理 | 成員、商務聯絡人、公告及設定 |
| 協作 | Communication Hub、訊息、論壇、AI 助理介面（AI 執行尚未驗證） |
| 使用體驗 | 中英文、桌面及手機響應式介面 |

## 技術架構

React 19、TypeScript 5.7、Vite 6、Tailwind CSS 4、React Router 7、i18next、Supabase JS 2、Chart.js、Leaflet、Vitest、Playwright。Node >=20.19.0。

## 展示登入

選擇 Admin、Worker 或 Owner 快速登入，無須註冊。所有身分與資料皆為虛構。

本 Repository 僅提供公開介紹文件，原始碼保持私人。展示版不代表正式系統已通過完整驗證。

## Release verification / 發布驗證

2026-11-26: the public demo was switched to the CI-passing release. Recorded local acceptance: 3,523 tests across 457 files; 42/42 mock browser E2E checks; production dependency audit reported zero known advisories at release time. Hosted runtime and cloud AI are not certified; development dependency advisories remain. Public browser role-by-role retesting is pending.
