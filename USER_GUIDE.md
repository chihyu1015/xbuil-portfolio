# User guide / 使用指南 (draft)

This is a navigation-level guide, not a fully tested step-by-step manual. Role-specific permissions and write workflows require further browser validation.

## Start / 開始

Open the public demo URL in README. Choose the one-click Admin, Worker or Owner demo login. 無須註冊或手動輸入密碼。 Do not enter real employee or customer data.

| Role | Suggested walkthrough / 建議展示流程 |
|---|---|
| Admin 管理員 | Home → Project list → Project detail → Salary list → Company monthly report |
| Worker 工人 | Project list → assigned site selection → reload to check site persistence; attendance and pay views require further role-specific validation |
| Owner 業主 | Select owner role → project list; confirm visible project and payment information under that role before demonstrating |

## Language and mobile / 語言與手機

Use Settings to select Traditional Chinese or English. The local release report records language persistence across reload. For mobile, use a narrow browser viewport or Chrome device emulation or the demo Mobile Preview switcher. The 390px project-list viewport was locally checked. The desktop avatar clipping fix passed recorded local acceptance; Settings also provides logout.

## Troubleshooting / 問題處理

App demo sign-in is required. Data is browser-local, not shared across devices or visitors. Do not clear storage unless you intend to discard your local demo changes. Report unexpected results with role, route, viewport, steps and screenshot without real personal data.

## Release verification / 發布驗證

2026-11-26: the public demo was switched to the CI-passing release. Recorded local acceptance: 3,523 tests across 457 files; 42/42 mock browser E2E checks; production dependency audit reported zero known advisories at release time. Hosted runtime and cloud AI are not certified; development dependency advisories remain. Public browser role-by-role retesting is pending.
