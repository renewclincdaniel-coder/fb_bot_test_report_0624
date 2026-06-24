# Facebook 智能客服 · 測試成效與下一步（2026-06-24）

這個 repo 保存「Facebook 智能客服現況 × 對話終點分析」的 HTML 簡報與來源 Markdown 報告。

## 線上簡報

GitHub Pages 部署後，可用以下網址查看：

https://renewclincdaniel-coder.github.io/fb_bot_test_report_0624/

操作方式：

- 方向鍵 / 空白鍵：切換頁面
- `F`：全螢幕
- `O`：頁面總覽
- `S`：演講者模式（含每頁備註 / 逐字稿）
- `T`：切換主題（預設 aurora 極光）

## 內容大綱（15 頁）

1. 封面 → 2. 一頁看懂 → 3. 背景（8,637 段真實對話、數據已驗證）
4. 核心發現（80.28% 已讀不回）→ 5. 流失斷點拆解 → 6. 客人旅程漏斗
7. 反直覺發現（自然流量轉換更高）→ 8. 智能客服現況能力＋範例
9. DeepEval 測試成績單 → 10. 最大機會（隔天主動追蹤 +25%～+50%）
11. 落地前提（Messenger 24h 規則）→ 12. 時程（M1/M2/M3）
13. 能多快（可壓縮 vs 壓不動）→ 14. 結論 → 15. 謝謝

## 檔案

- `index.html`：HTML 簡報（aurora 主題）
- `assets/`：html-ppt-skill runtime、字體、基礎樣式與動畫
- `data/智能客服現況對照終點分析報告_20260624.md`：來源完整報告

## 數據可信度

簡報所有統計數字皆已對照原始 Facebook 後台匯出資料逐筆驗證：總對話數 8,637、四個入口分布（7,173 / 840 / 614 / 10）、各終點佔比，獨立重算與官方分析流程 100% 一致。

## 簡報工具

使用 [html-ppt-skill](https://github.com/lewislulu/html-ppt-skill)（aurora theme）製作，純靜態 HTML/CSS/JS。
