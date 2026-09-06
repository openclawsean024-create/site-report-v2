# Changelog · site-report-v2 PRD

所有 PRD / SPEC 變更記錄於此。最新在上。

---

## [v3.0.2] · 2026-09-06 · fleet-upgrade

### Added（新增）
- §1 產品概述（v3.0 結構：問題 / Persona / Value Prop / KPIs / Non-Goals）
- §2 使用者場景與流程（6 個 User Stories + 4 個 edge cases）
- §3 功能需求（20 FR + 10 AC，10 P0 + 6 P1 + 4 P2）
- §4 Non-Functional Requirements（性能 + 安全 + 降級）
- §5 技術架構（9 層技術棧 + 系統架構圖 + Prisma schema）
- §6 Definition of Done（7 條 checkbox）
- §7 部署契約（Pages 部署 + Vercel 規劃 + 環境變數）
- §8 Out of Scope（7 條明確排除）
- §9 變更日誌（即本文件）
- 附錄 A：v2.2.1 完整 821 行規格保留於 `../SPEC.md`
- 版本號升級 v2.2.1 → v3.0.2
- 標頭加入 fleet-upgrade 標記 + 部署目標明確為 GitHub Pages

### Changed（變更）
- 升級對齊 SPEC v3.0 契約（fleet 統一規格）
- 部署目標從「待 Vercel 部署」→ **GitHub Pages**（純靜態 demo，Vercel 留為未來完整後端）
- 結構重整：v2.2.1 20 個 FR 集中於 §3 表格化

### Status
- 純靜態 HTML 1 個入口（dashboard.html, ~307 行）
- 完整 v2.2.1 規格書保留為 historical reference
- 4 個降級策略（GPS / 人臉 / 離線 / LINE）
- GHA: ✅ ci.yml 建立（Pages deploy）

---

## [v2.2.1] · 2026-07-11 · 規格完整版

### Added
- §1 產品概述（5 子節：問題 / Persona / Value Prop / KPIs / Non-Goals）
- §2 使用者場景（6 US + 4 edge cases）
- §3 功能需求（20 FR：10 P0 + 6 P1 + 4 P2）
- §3.4 10 條 AC（Given/When/Then）
- §4 系統設計（9 層技術棧 + 系統架構圖 + Prisma 完整 schema）
- §5 非功能性需求（性能 + 安全 + 降級）
- §6+ 風險 / 里程碑 / 定價
- 完整 821 行

### Status
- 規格階段，無 demo
- 後續 Sprint 1 預計部署 Next.js 14 + face-api.js + Supabase + Vercel
- 5,000+ 駐點服務公司 + 3,000 工地管理 + 2,000 工讀生派遣

### Notes
- sweet spot：中（GPS + 人臉雙驗證為核心差異化）
- 預期 MRR：M6 NT$100K / M12 NT$500K
- 500 萬次/月打卡支撐

---

*本文件由 fleet-upgrade worker 於 2026-09-06 自動生成。*
