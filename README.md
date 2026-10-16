# RD-JoeAI · AI 研究入口

Joe.ai.partner 的 Report Dashboard（GitHub Pages，由 `main` 分支根目錄發佈；原名 `AI_Dashboard`，2026-10-16 改名）。

**公開網址：https://jwai-partner.github.io/RD-JoeAI/**

全部內容由 AI 生成，僅供參考！

## 分類

**Architecture**／**AI tool list**／**LLM Model**（入口頁目前分成 AI 工具與產業、LLM 模型選型兩區；報告的 `cat` 欄位之後補上）。

## 結構

- 入口頁 `index.html` 的 `REPORTS_AI`、`REPORTS_LLM` 陣列列出所有報告。
- `reports.json` 是給 All-RD（Daddy Joe 的五合一 Report Dashboard）讀取的清單，新增報告時與入口頁一起更新。
- 報告放在 `reports/<YYYY-MM-DD>_<slug>/index.html`。
