# GitHub Portfolio Guide

這個 repository 是我 GitHub 的導覽頁，目的是提供一條清楚的閱讀路徑，而不是單純羅列所有專案。

我的背景橫跨財務分析、量化建模與系統導向的軟體開發，因此這裡的專案更重視「問題如何被拆解與重構」，而不只是功能或模型表現。

這份 portfolio 會持續滾動式更新。  
每個被選入的專案，除了說明做了什麼，也會標註：

- 初次完成的時間與背景脈絡
- 後續 refactor 的時間點與動機
- 現在這個版本想解決的問題

因此閱讀這份 GitHub 的方式，會比較像是在看一條隨時間演化的工程軌跡。

---

## 建議閱讀順序

如果你是第一次來，建議從下列幾個專案開始。  
它們代表我在不同階段的思考方式與重構能力。

---

### Airlines_DBMS  
Course project → Refactored system artifact  

**Initial version — 2023.12**  
當時的目標是學習 ER diagram、正規化與 relational schema 設計，前端只是輔助資料庫結構理解的工具。

**Refactor — 2026.02**  
將原本偏靜態的課程作業重構為可實際操作的系統：

- 重新設計使用流程，讓使用者可以直接體驗查詢
- 強化 schema 與 application layer 的對應關係
- 舊版本保留於 master，重構版本在新 branch

**這個專案現在代表的意義**  
如何把一個學術作業轉化為可重現、可互動的系統原型。

---

### stock_analysis  
Finance × quantitative workflow  

**Initial version — 2023.06（大二）**  
為申請 TMBA 交易部門所建立，當時以策略發想與基礎分析流程為主。

**Planned refactor — 2026.03**  
重構為研究導向的分析 pipeline：

- 模組化資料處理流程  
- 可重現的實驗結構  
- 以解釋與決策流程為核心輸出  

**這個專案現在代表的意義**  
從 script 型分析轉向具備研究結構的系統化工作流。

---

## 關於未公開的實務經驗

部分實習與產業專案因 NDA 無法公開。  
相關的設計模式與系統思維，會以抽象化或 toy implementation 的形式出現在公開 repository 中。

---

## 最後

這份 GitHub 比較像是一個持續維護的工程筆記，而不是完成品展示。

如果你是為了面試或合作而來，謝謝你從這份導覽開始閱讀。


# GitHub Portfolio Guide

This repository serves as a navigation guide to my GitHub.

Instead of showcasing isolated projects, this portfolio is organized to reflect how my work evolves over time — how problems are framed, how systems are redesigned, and how earlier work is revisited with new standards.

My background spans financial analysis, quantitative modeling, and system-oriented software development.  
Therefore, the focus here is on structure, reproducibility, and design decisions rather than surface-level performance.

This portfolio is continuously evolving.  
For each selected project, I document:

- when it was first built and in what context  
- when and why it was refactored  
- what the current version is trying to achieve  

Reading this GitHub is closer to reading an engineering timeline than a collection of finished products.

---

## Where to start

If this is your first time here, I recommend starting with the following projects.

They represent how my thinking and implementation have changed across different stages.

---

### Airlines_DBMS  
Course project → Refactored system artifact  

**Initial version — Dec 2023**  
The original goal was to learn ER modeling, normalization, and relational schema design.  
The frontend only served as a tool to understand the database structure.

**Refactor — Feb 2026**  
Rebuilt as an interactive and usable system:

- redesigned query exploration flow  
- clearer mapping between schema and application layer  
- legacy version preserved in `master`  
- refactored implementation in a new branch  

**What it represents now**  
Turning a static academic artifact into a reproducible and interactive system prototype.

---

### stock_analysis  
Finance × quantitative workflow  

**Initial version — Jun 2023 (sophomore year)**  
Built for applying to the TMBA trading program.  
At that time it focused on strategy exploration and basic analysis flow.

**Planned refactor — Mar 2026**  
Reorganizing into a research-oriented pipeline:

- modular data ingestion  
- reproducible experiment structure  
- interpretation-first outputs  

**What it represents now**  
The transition from script-based analysis to a structured research workflow.

---

## On industry experience

Some industry projects are not publicly available due to NDA constraints.  
Their design patterns and system thinking are reflected in the public repositories through abstracted or toy implementations.

---

## Final note

This GitHub is a maintained engineering archive rather than a highlight reel.

If you are here for an interview or collaboration, I appreciate you starting from this guide.
