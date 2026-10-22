# 📰 Tech News Daily

> 由 **Hermes Agent** 每日自動聚合的高品質技術資訊庫，涵蓋前端、後端與 AI 三大領域。

---

## 🗓️ 今日頭條 (Latest)

| 領域 | 今日最重要一則 |
|------|--------------|
| 🎨 前端 | [共用表單元件漏接欄位提示，造成讀屏器無法取得說明 (Four form components hold every form in our app, and writing this post found the one bug in them)](./frontend/daily/2026-10-22.md) |
| ⚙️ 後端 | [快取很容易，失效才是系統故障的起點：實務指南 (Caching Is Easy. Cache Invalidation Is Where Systems Break: A Practical Guide)](./backend/daily/2026-10-22.md) |
| 🤖 AI | [代理快取工程：直接管理 KV 狀態而不重算對話歷史 (Cache Engineering for Agents)](./ai/daily/2026-10-22.md) |

---

## 🚪 領域傳送門

| 領域 | 描述 | 連結 |
|------|------|------|
| 🎨 **前端** | 框架釋出、效能優化、建置工具 | [進入前端大廳 →](./frontend/README.md) |
| ⚙️ **後端** | 架構探討、資料庫、API 設計、資安 | [進入後端大廳 →](./backend/README.md) |
| 🤖 **AI** | LLM 更新、AI 開發工具、Agent 設計 | [進入 AI 大廳 →](./ai/README.md) |

---

## 📂 專案結構

```text
📦 tech-news-daily
 ┣ 📂 frontend/
 ┃ ┣ 📂 archives/                 # 前端歷史歸檔 (存放超過 7 天的內容)
 ┃ ┣ 📂 daily/                    # 前端每日日誌 (YYYY-MM-DD.md)
 ┃ ┗ 📜 README.md                 # 前端領域大廳與最近 7 日索引
 ┣ 📂 backend/
 ┃ ┣ 📂 archives/                 # 後端歷史歸檔
 ┃ ┣ 📂 daily/                    # 後端每日日誌 (YYYY-MM-DD.md)
 ┃ ┗ 📜 README.md                 # 後端領域大廳與最近 7 日索引
 ┣ 📂 ai/
 ┃ ┣ 📂 archives/                 # AI 歷史歸檔
 ┃ ┣ 📂 daily/                    # AI 每日日誌 (YYYY-MM-DD.md)
 ┃ ┗ 📜 README.md                 # AI 領域大廳與最近 7 日索引
 ┗ 📜 README.md                   # 專案總大廳與今日各領域頭條
```