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

## 🔎 快速導覽（給不同背景的招募者）

不同領域的招募者可以從下表快速找到最相關的專案與技術內容。

| 如果你正在找…                               | 建議閱讀的 repositories                                                                                                                                                                                                       | 你會看到的能力與內容                                                     |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------- |
| Finance × AI / Quant / FinTech        | [GLoVE](https://github.com/datafox-tw/GLoVE) <br> [robo_advisor](https://github.com/datafox-tw/robo_advisor) <br> [Meme_stock_analysis_and_prediction](https://github.com/datafox-tw/Meme_stock_analysis_and_prediction) | GARCH × 深度學習混合建模、模組化金融分析系統、另類資料與市場訊號研究                         |
| LLM / RAG / NLP 系統開發                  | 深度學習 HW3 – RAG system <br> [IRTM_project](https://github.com/datafox-tw/IRTM_project) <br> Toxic Comment Detector（BERT & GPT 版本）                                                                                         | Retriever / reranker 微調、繁體中文 RAG 策略實驗、LLM 出現前後的完整 NLP pipeline |
| LLM 微調 / Transformer 訓練               | Instruction tuning（QLoRA） <br> Chinese Extractive QA（BERT）                                                                                                                                                               | 參數高效微調、span prediction 訓練流程、prompt 與推論策略設計                     |
| Machine Learning / Deep Learning 基礎能力 | [data_analysis](https://github.com/datafox-tw/data_analysis) <br> AI Cup 3D 醫學影像                                                                                                                                         | End-to-end 建模流程、時間序列預測、論文復現與實驗設計能力                             |
| 系統整合 / 全端工程                           | [CloudNative_Stadium_System](https://github.com/datafox-tw/CloudNative_Stadium_System) <br> [Airlines_DBMS](https://github.com/datafox-tw/Airlines_DBMS)                                                                 | React + Express 架構、API 測試與壓力測試、資料庫 schema 與交易設計                |
| 推薦系統 / 資料探勘                           | [BDA2023_final_apriori](https://github.com/datafox-tw/BDA2023_final_apriori)                                                                                                                                             | 關聯規則推薦系統與商業問題轉換能力                                              |
| 產品導向的 AI 應用                           | [youtube_nlp_analysis](https://github.com/datafox-tw/youtube_nlp_analysis)                                                                                                                                               | 從使用者資料推導內容策略與商業洞察                                              |
| 程式設計基礎與系統思維起點                         | [PBC2021-final](https://github.com/datafox-tw/PBC2021-final) <br> [windowskill](https://github.com/datafox-tw/windowskill)                                                                                               | OOP 設計、互動式系統實作、C++ 與 Python 的實作差異                              |

---

## 🧭 建議閱讀路線

如果只有幾分鐘：

* **GenAI / LLM 職缺 →** RAG system → IRTM → QLoRA
* **Quant / FinTech 職缺 →** GLoVE → Robo-advisor
* **軟體工程 / 全端 →** Cloud Native → DBMS
* **ML Engineer →** Data Analytics → AI Cup

如果你有更多時間，歡迎來讀：
[每一份Project的介紹與技能棧堆疊過程](https://github.com/datafox-tw/portfolio/blob/main/Projects_timeline.md)
[我的履歷]()
[我的自我介紹，讓你更認識我]()
[我的成績單](https://github.com/datafox-tw/portfolio/blob/main/koyuchi_transcript.pdf)
---

## 💡 我主要關注的方向

我目前的核心主線是：

* LLM / RAG 系統設計與最佳化
* Finance × AI 的可驗證建模
* 可落地的 Machine Learning 系統

---

## 建議閱讀順序

如果你是第一次來，不確定要讀哪些專案，建議從下列幾個專案開始。  
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

## 🔎 Quick Guide for Recruiters

Different visitors may be interested in different aspects of my work.
This table helps you quickly find the most relevant repositories.

| If you are looking for…                       | Recommended repositories                                                                                                                                                                                                 | What you will see                                                                                                    |
| --------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------------------------------------------------------------------- |
| Finance × AI / Quant / FinTech                | [GLoVE](https://github.com/datafox-tw/GLoVE) <br> [robo_advisor](https://github.com/datafox-tw/robo_advisor) <br> [Meme_stock_analysis_and_prediction](https://github.com/datafox-tw/Meme_stock_analysis_and_prediction) | Hybrid modeling of GARCH × deep learning, modular financial analysis system, alternative data for market signals     |
| LLM / RAG / NLP systems                       | Deep Learning HW3 – RAG system <br> [IRTM_project](https://github.com/datafox-tw/IRTM_project) <br> Toxic Comment Detector (BERT & GPT versions)                                                                         | Retriever & reranker fine-tuning, Traditional Chinese RAG strategy study, full NLP pipeline before and after LLM era |
| LLM fine-tuning / Transformer                 | Instruction tuning (QLoRA) <br> Chinese Extractive QA (BERT)                                                                                                                                                             | Parameter-efficient fine-tuning, span prediction training pipeline, prompt & inference strategy design               |
| Machine Learning / Deep Learning fundamentals | [data_analysis](https://github.com/datafox-tw/data_analysis) <br> AI Cup 3D medical imaging                                                                                                                              | End-to-end modeling, time-series prediction, paper reproduction, experimental design                                 |
| Full-stack / System integration               | [CloudNative_Stadium_System](https://github.com/datafox-tw/CloudNative_Stadium_System) <br> [Airlines_DBMS](https://github.com/datafox-tw/Airlines_DBMS)                                                                 | React + Express architecture, API testing & load testing, relational schema & transaction design                     |
| Recommender / Data mining                     | [BDA2023_final_apriori](https://github.com/datafox-tw/BDA2023_final_apriori)                                                                                                                                             | Association-rule-based recommendation and business problem formulation                                               |
| Product / Applied AI thinking                 | [youtube_nlp_analysis](https://github.com/datafox-tw/youtube_nlp_analysis)                                                                                                                                               | Turning user data into actionable content and business insights                                                      |
| Programming foundations                       | [PBC2021-final](https://github.com/datafox-tw/PBC2021-final) <br> [windowskill](https://github.com/datafox-tw/windowskill)                                                                                               | Object-oriented design, interactive systems, C++ vs Python implementation mindset                                    |

---

## 🧭 Suggested Reading Paths

If you only have a few minutes:

* **LLM / GenAI roles →** RAG system → IRTM → QLoRA
* **Quant / FinTech roles →** GLoVE → Robo-advisor
* **Software / Full-stack roles →** Cloud Native system → DBMS
* **ML engineer roles →** Data Analytics → AI Cup


## Where to start

If this is your first time here, and not sure which one is better for you, I recommend starting with the following projects.

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
