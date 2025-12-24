
---

# frontend/02-ssr.md

```markdown
# Server-Side Rendering（PHP / JSP / ASP.NET）

## 為何出現？

- 登入需求
- 使用者狀態
- 資料庫與商業邏輯

## 核心特性

- 狀態在 Server
- HTML 是即時產生的結果

## 問題

- 每次互動都整頁刷新
- UX 開始落後

---

## 架構模型

```mermaid
flowchart LR
    Browser --> Server
    Server -->|HTML| Browser
    Server --> DB[(Database)]
