# UndergroundRemake 概念 Spec 規則

- 本 repo 是 Module Spec git
- 產品為 UndergroundRemake
- module id 為 `no1_concept`
- 本 repo 承載概念階段規格

## 多層配對

- Product git 承載上游規劃
- Design git 尚未建立
- Impl git 尚未建立
- 本 repo 是目前唯一 Module 層
- 配對以 `product-scope` 的註冊表為準

---

## 當前內容

- Logic 層已有載具物理引擎規格
- Model 層目前待補
- View 層目前待補

---

## 原生工作規則

- 任何改動先使用 `product-scope`
- 所有 Spec 改動使用 `code-spec`
- Markdown 改動使用 `doc-markdown`
- 不得假設 Design 或 Impl 已存在
- 新增下游前先補上游對應
- 跨層 branch 名稱必須一致
- 配對 commit 內容必須一致

---

## 相容與漂移控制

- `AGENTS.md` 是本目錄的規則真相
- `CLAUDE.md` 只保留 Claude Code 入口
- 產品規則不得複製回相容入口
- 漂移檢查確認相容入口只含導向規則
