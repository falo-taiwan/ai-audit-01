# C00~C08 方法論索引

本文件用來整理 TAAT x FALO Governance Runtime 的第一層方法論索引。這裡只定義 C00~C08 的用途與邊界，不展開完整 SOP 內容。

## 索引目的

CXX 索引的目的，是讓本專案在方法論建立期可以維持一致語言：

- C00~C02：定義治理背景、範圍與文件系統。
- C03~C05：整理 SOP、Computer Audit、Workflow / ERP Mapping。
- C06~C08：逐步延伸到 Auditability、AI-assisted Governance 與 Runtime 維運。

## C00. Project Context

用途：

- 說明本專案背景、角色、目標、限制與導入順序。
- 作為所有文件的共同起點。

目前對應文件：

- `docs/00_context/PROJECT_CONTEXT.md`

狀態：

- 初版建立中。

## C01. Governance Principles

用途：

- 定義治理優先、漸進導入、HITL-first、Traceability-first 等原則。
- 避免專案過早變成全自動 Agent 或單純 AI Demo。

目前對應文件：

- `AGENTS.md`
- `README.md`

狀態：

- 初版建立中。

## C02. Documentation Runtime

用途：

- 定義文件如何成為治理 Runtime 的一部分。
- 連接 SOP、Workflow、ERP、Audit Trail、Log、權責與表單。

目前對應資料夾：

- `docs/00_context/`
- `docs/03_sop_framework/`
- `docs/06_outputs_html/`

狀態：

- 先建立骨架，後續再定義模板與輸出規則。

## C03. SOP Governance Framework

用途：

- 建立 SOP 文件架構、Level 2 + Level 3 混合型文件方向。
- 定義流程、控制點、權責與表單的關係。

目前對應資料夾：

- `docs/03_sop_framework/`

狀態：

- 尚未展開 SOP 內容。

## C04. Computer Audit Framework

用途：

- 定義 Computer Audit 的稽核視角。
- 釐清系統紀錄、操作紀錄、例外紀錄、版本紀錄與證據需求。

目前對應資料夾：

- `docs/04_computer_audit/`

狀態：

- 尚未展開稽核程序。

## C05. Workflow / ERP Mapping

用途：

- 對應企業流程、ERP 模組、表單欄位與資料流。
- 將 SOP 與系統資料結構連接起來。

目前對應資料夾：

- `docs/05_workflow_erp_mapping/`

狀態：

- 尚未建立欄位 Mapping。

## C06. Digital Auditability

用途：

- 建立數位可稽核性的語言與框架。
- 關注 Evidence Chain、Workflow Lineage、版本、時間戳、權限與防竄改。

目前對應資料夾：

- `docs/04_computer_audit/`
- `docs/05_workflow_erp_mapping/`

狀態：

- 作為後續延伸方向，先不產品化。

## C07. AI-assisted Governance

用途：

- 定義 AI 可以協助治理文件、研究整合、Cross-AI Validation 與稽核準備的範圍。
- 明確保留 HITL 與人類決策責任。

目前對應資料夾：

- `docs/01_research_raw/`
- `docs/02_research_synthesis/`

狀態：

- 暫以輔助研究與文件整理為主。

## C08. Governance Runtime Maintenance

用途：

- 定義治理文件如何維護、歸檔、版本化與輸出。
- 確保專案可以長期維運，而不是一次性文件。

目前對應資料夾：

- `docs/06_outputs_html/`
- `docs/99_archive/`

狀態：

- 初期只建立資料夾與歸檔邏輯。

## CXX 使用規則

- CXX 是方法論索引，不是完整 SOP。
- 新文件應先歸入對應 CXX，再決定是否需要展開。
- 若某內容同時屬於多個 CXX，先放在主要用途所在位置，再用 Cross-reference 連結。
- 未經 ff 確認前，不把 CXX 內容宣稱為定版方法論。
