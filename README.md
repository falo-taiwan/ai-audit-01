# TAAT x FALO Governance Runtime

本專案用來建立 TAAT / FALO 的 AI-native Governance Methodology。它不是 AI 炫技專案，也不是一開始就要做全自動 Agent，而是先把台灣企業可落地的治理文件、流程、稽核軌跡與系統對應關係整理成可維護的 Runtime。

目前主軸：

- SOP Governance
- Computer Audit
- Workflow
- ERP Mapping
- Audit Trail
- Documentation Runtime
- AI-assisted Governance
- HITL
- Cross-AI Validation

## 1. 專案目的

本專案目標是建立一套符合台灣企業 reality 的治理方法論，讓文件不只是靜態資料，而能成為治理 Runtime 的一部分。

這裡的 Runtime 不是指單一軟體系統，而是指一組可持續運作的治理結構：

- 誰負責
- 做什麼流程
- 用什麼表單
- 留下什麼紀錄
- ERP 或系統如何對應
- 哪些地方需要稽核
- 哪些地方需要 HITL
- AI 可以協助到哪裡
- AI 不可以取代哪裡

## 2. TAAT / FALO 背景

TAAT / FALO 目前仍處於治理方法論建立與概念對齊階段，不應過早被描述成固定產品規格。

目前工作理解如下：

| 名稱 | 直覺定位 | 主要關注 |
| --- | --- | --- |
| FALO | 落地層 | Workflow、KM、ETL、教學、方法論展開 |
| TAAT | 可信層 | Governance、Audit Trail、Evidence Chain、可稽核 runtime |

也可以用雙軌方式理解：

- FALO Open Pattern：把流程、方法、教學與可理解的治理模式展開。
- TAAT Sealed Runtime：把治理核心、證據鏈、權限、版本、稽核軌跡等可信元件封裝保護。

## 3. Pilot Case

目前 Pilot Case：

> 工程承攬業銷售與收款循環

這個案例適合作為第一個治理樣板，因為它同時包含：

- 客戶與合約
- 報價與訂單
- 工程進度與驗收
- 請款與發票
- 收款與沖帳
- 權責分工
- ERP 資料流
- 內控控制點
- 稽核證據需求

本階段不先展開完整 SOP 細節，而是先建立方法論、文件骨架與治理邊界。

## 4. 目前階段

目前階段：

> SOP / Computer Audit / Workflow / ERP Mapping

導入順序如下：

1. 內控 / SOP
2. Computer Audit
3. Workflow / ERP Mapping
4. Digital Auditability
5. AI-assisted Governance
6. 未來逐步延伸 AI Audit

## 5. 文件結構

```text
docs/
  00_context/
  01_research_raw/
  02_research_synthesis/
  03_sop_framework/
  04_computer_audit/
  05_workflow_erp_mapping/
  06_outputs_html/
  99_archive/
```

各資料夾用途：

- `00_context/`：專案背景、角色、方法論索引、治理限制。
- `01_research_raw/`：原始研究材料與 AI 輸出。
- `02_research_synthesis/`：研究整合與 Cross-AI Validation。
- `03_sop_framework/`：SOP 架構與模板。
- `04_computer_audit/`：Computer Audit 架構與稽核證據。
- `05_workflow_erp_mapping/`：Workflow、ERP、表單與欄位對應。
- `06_outputs_html/`：HTML 人讀版與教學展示輸出。
- `99_archive/`：舊版、備份與歷史材料。

## 6. 第一階段產出

第一階段只建立治理骨架，不展開完整 SOP。

目前應優先維護：

- `AGENTS.md`：AI 協作規則與治理邊界。
- `README.md`：專案目的與目前階段。
- `docs/00_context/CXX_INDEX.md`：C00~C08 方法論索引。
- `docs/00_context/PROJECT_CONTEXT.md`：專案背景、角色、目標、限制與導入順序。

## 7. 核心原則

本專案所有文件與後續實作，都應遵守：

> 治理優先、漸進導入。

也就是：

- 先理解治理目的，再整理流程。
- 先定義權責與證據，再導入工具。
- 先建立可稽核文件，再談 AI 協助。
- 先保留 HITL，再逐步評估自動化。
