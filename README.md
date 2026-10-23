# 店長排班系統

## 10 分鐘上線
1. `npm install && npm run dev` 先用 localStorage 演示。
2. 在 Supabase SQL Editor 執行 `schema.sql`。
3. GitHub Settings → Secrets 加入 `SUPABASE_URL`、`SUPABASE_ANON_KEY`；推送到 main 後由 Actions 部署 GitHub Pages。
4. 推送金鑰可加 `WECOM_WEBHOOK`、`PUSHPLUS_TOKEN`、`SCT_KEY`、`CUSTOM_WEBHOOK`，再接入週日 cron 腳本。

個人微信群沒有官方 API；可用企業微信群機器人或 PushPlus/Server 醬推給店長，再由店長轉發群內。
