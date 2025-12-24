# 00 · Frontend 演進總覽

## 核心問題

- 畫面如何更新？
- 誰是真相？
- 狀態放在哪？

```mermaid
flowchart TB
    State --> UI
    UI --> Event
    Event --> State
```

本篇後續章節，皆用同一個 Todo 功能做對照。