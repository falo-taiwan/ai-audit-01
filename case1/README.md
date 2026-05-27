# 工程承攬業銷售與收款循環治理工作稿

本專案目前定位為公司稽核主管個人使用的治理文件工作區，用來整理「工程承攬業銷售與收款循環」的內控、SOP、Workflow、ERP 對應、證據留存與 Computer Audit 檢查基礎。

本工作區不是全集團正式制度，也不是對外服務提案或資訊系統建置規格。現階段目標是先形成一份可閱讀、可討論、可維護、可逐步校閱的治理型文件。

## 1. 目前目的

本專案協助稽核主管先回答幾個核心問題：

- 這個流程從合約到收款，到底管哪些事？
- 哪些節點最容易出錯？
- 誰應該負責建立、審核、核准、覆核與留存？
- 哪些表單、附件、紀錄與系統 Log 需要保留？
- ERP / Workflow 的資料是否能支撐內控與稽核判斷？
- Computer Audit 可以如何協助找出例外與時序異常？

## 2. Pilot Case

目前 Pilot Case 為：

> 工程承攬業銷售與收款循環

流程範圍包含：

1. 合約建立與核准。
2. 合約變更與授權。
3. 工程估驗。
4. 請款與發票。
5. 收款與沖帳。
6. 保留款管理。
7. 驗收與結案。
8. 異常追蹤與改善。

## 3. 文件分層

本專案目前採 S / A / B 三層對照：

| 文件 | 定位 | 主要讀者 |
| --- | --- | --- |
| S 版 Sample Version | 傳統上市櫃 SOP / 內控制度 reality，作為市場現況 baseline | 董事會、內稽、財會、營運、工程主管、ERP 顧問 |
| A 版治理主文件 | Level 2 + Level 3 混合型治理文件，聚焦內控、SOP、權責、流程、KCP、表單與 Workflow 基礎 | 董事會、內稽、財會、營運、工程主管 |
| B 版 Computer Audit 附加版本 | 以主文件為基礎，加深 ERP、Workflow、Audit Trail、Log、SoD、例外清單與可疑時序 | 稽核主管、電腦稽核、資訊、ERP 相關人員 |

S 版不是 A 版或 B 版的簡化稿，而是傳統治理世界本來就存在的正式 SOP 樣貌。

## 4. 導入順序

目前遵守循序漸進原則：

```text
內控 / SOP
  -> Computer Audit
  -> Workflow / ERP
  -> 系統留痕與例外清單
  -> 管理追蹤與稽核覆核
```

現階段不直接做：

- 全自動稽核。
- 系統自動判定違規。
- 自動核准或否決工程款。
- 對外服務包裝。
- 過度技術化的系統規格書。

## 5. 目前主要輸出

### 主頁

- `index.html`：公司稽核主管個人工作稿入口頁。
- `research-pack-index.html`：已改為導向主頁的相容入口。

### 核心文件

- `docs/03_sop_framework/EPC_SALES_COLLECTION_GOVERNANCE_SAMPLE_v0.1.md`
- `docs/06_outputs_html/EPC_SALES_COLLECTION_GOVERNANCE_SAMPLE_v0.1.html`
- `docs/03_sop_framework/EPC_SALES_COLLECTION_GOVERNANCE_v0.2.md`
- `docs/06_outputs_html/EPC_SALES_COLLECTION_GOVERNANCE_v0.2.html`
- `docs/03_sop_framework/EPC_SALES_COLLECTION_GOVERNANCE_CA_v0.2.md`
- `docs/06_outputs_html/EPC_SALES_COLLECTION_GOVERNANCE_CA_v0.2.html`

### Special Case

疑似違建 / 未合法申報施工：

- `docs/04_computer_audit/SPECIAL_CASE_PROJECT_AUDIT.md`
- `docs/06_outputs_html/SPECIAL_CASE_PROJECT_AUDIT.html`
- `docs/04_computer_audit/SPECIAL_CASE_PROJECT_CHECKLIST.md`
- `docs/06_outputs_html/SPECIAL_CASE_PROJECT_CHECKLIST.html`
- `docs/04_computer_audit/SPECIAL_CASE_COMPUTER_AUDIT_SUPPORT.md`
- `docs/06_outputs_html/SPECIAL_CASE_COMPUTER_AUDIT_SUPPORT.html`

## 6. 文件原則

所有核心治理文件原則上維持雙格式：

- Markdown：便於版本控管、差異比對、後續整理與系統化。
- Single-file Responsive HTML：便於人類閱讀、教學、展示與內部討論。

文件撰寫原則：

- 先講流程與權責，再講系統資料。
- 先讓主管看得懂，再補充稽核細節。
- 表格、控制點、證據鏈需可追溯。
- Computer Audit 只作為檢查與例外提示，不取代人工判斷。
- 重要判斷仍由稽核主管、法務、工程專業人員或相關權責主管負責。

## 7. 資料夾

`docs/00_context/`：專案背景與工作脈絡。

`docs/01_research_raw/`：原始研究資料與參考材料，不視為正式文件。

`docs/02_research_synthesis/`：研究整合與收斂觀點。

`docs/03_sop_framework/`：治理主文件、SOP 架構與控制點設計。

`docs/04_computer_audit/`：Computer Audit、例外規則、時序檢查與專案稽核案例。

`docs/05_workflow_erp_mapping/`：Workflow、ERP 模組、表單欄位與資料流 Mapping。

`docs/06_outputs_html/`：人讀版 HTML 輸出。

`docs/99_archive/`：舊版、被取代版本、早期研究包與歷史備份。
