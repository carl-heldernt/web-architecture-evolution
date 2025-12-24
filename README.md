# Web Architecture Evolution
> 前後端架構演進的學習筆記（Frontend 篇）

本 Repo 用來整理 Web 架構的**演進邏輯與因果關係**，  
不是框架教學，而是工程思維的建立。

---

## Frontend 演進總覽

```mermaid
flowchart LR
    HTML["HTML<br/>Document"] --> SSR["Server Rendering<br/>PHP / JSP / ASP.NET"]
    SSR --> AJAX["AJAX + jQuery<br/>DOM Driven"]
    AJAX --> AngularJS["AngularJS<br/>Data Driven UI"]
    AngularJS --> Modern["React / Vue / Angular<br/>Component"];
