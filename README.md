# Bowling Lane Alert

ボウリング大会・空きレーン通知

## Repository

Recommended repository name: `bowling-lane-alert`

## Domain candidates

Confirmed domain: `lanealert.jp`

Other candidates:

- `lanealert.jp`
- `bowlalert.jp`
- `bowlinglane.jp`
- `bowlmatch.jp`

## Concept

大会、空きレーン、スコアランキング更新を通知し、施設送客、用品、イベント掲載へつなげる。

## Technical Selection

- Frontend: Vite + React 19
- Styling: Plain CSS
- Initial data: Static alert seed records in `src/App.jsx`
- Local state: localStorage for MVP saved alerts and UGC requests
- Notification integrations: LINE Messaging API, X API, transactional email provider, Slack Incoming Webhooks
- Future data layer: Supabase or Cloudflare D1
- SEO/AIO/LLMO: structured data, answer block, FAQ, sitemap, robots and `llms.txt`

## Revenue Paths

- 施設送客
- 用品 affiliate
- イベント掲載
- 会員課金
- スポンサー

## Commands

```bash
npm install
npm run dev
npm run lint
npm run build
```
