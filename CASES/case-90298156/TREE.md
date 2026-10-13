# case-90298156 目錄樹

本資料夾集中本案所有現行內容；舊編號60298156及CASE-2026-001在同一案件內保留對照。受限本機資料與Git文件分開。

```text
case-90298156/
├── actions/
│   └── next-steps.md
├── archive/
│   └── legacy-case-index.md
├── audit/
│   ├── 2026-10-11/
│   │   ├── 00-management-summary.md
│   │   ├── 01-executive-decision-memo.md
│   │   ├── 02-evidence-liability-matrix.md
│   │   ├── 03-legal-liability.md
│   │   ├── 04-case-law-comparison.md
│   │   ├── 05-medical-risk.md
│   │   ├── 06-financial-exposure.md
│   │   ├── 07-defence-settlement-strategy.md
│   │   ├── 08-customer-response-drafts.md
│   │   ├── 09-action-checklist.md
│   │   ├── 10-source-verification.md
│   │   └── README.md
│   ├── 2026-10-12/
│       ├── device-parameter-review.md
│       ├── evidence-update.md
│       ├── hypothetical-best-case-recollection.md  [純假設，不是證據]
│       ├── medical-expense-support.md
│       ├── records-gap-and-response-plan.md
│       └── two-week-recovery-cost-scenarios.md  [預算假設]
│   └── 2026-10-13/
│       └── customer-escalation.md
├── evidence/
│   ├── private-local/  [本機受限，不追蹤Git]
│   │   ├── restricted/  核查附錄及來源雜湊
│   │   └── source-work/  工作副本、OCR及支援
│   ├── README.md
│   └── storage-and-access.md
├── financial/
│   ├── README.md
│   └── exposure-model.xlsx
├── responses/
│   ├── archive/
│   │   └── CASE-2026-001-replies.md
│   ├── 2026-10-13-escalation-acknowledgment.md
│   ├── 2026-10-13.md
│   ├── 2026-10-20.md
│   ├── README.md
│   └── settlement-discussion.md
├── AGENTS.md
├── CASE.md
├── README.md
└── TREE.md
```

## 主要入口

| 工作 | 路徑 |
| --- | --- |
| 接手案件 | [README.md](README.md)、[AGENTS.md](AGENTS.md) |
| 更新事實及爭點 | [CASE.md](CASE.md) |
| 更新進度與完成證明 | [actions/next-steps.md](actions/next-steps.md) |
| 查看現行草稿及批准／發送狀態 | [responses/README.md](responses/README.md) |
| 查看研究及來源 | [audit/2026-10-11/README.md](audit/2026-10-11/README.md) |
| 查看新增證據及影響 | [audit/2026-10-12/evidence-update.md](audit/2026-10-12/evidence-update.md) |
| 查設備設定及時鐘限制 | [audit/2026-10-12/device-parameter-review.md](audit/2026-10-12/device-parameter-review.md) |
| 查紀錄缺口及20日更新選項 | [部署](audit/2026-10-12/records-gap-and-response-plan.md) |
| 查971支援及實際付款狀態 | [audit/2026-10-12/medical-expense-support.md](audit/2026-10-12/medical-expense-support.md) |
| 查看最有利回憶書純假設及條件分析 | [模擬](audit/2026-10-12/hypothetical-best-case-recollection.md) |
| 使用財務模型 | [financial/README.md](financial/README.md) |
| 查找證據位置與可及限制 | [evidence/README.md](evidence/README.md) |

`evidence/private-local/`只在本機，不能在GitHub下載；原始圖片、對話和病歷仍受限。更新結構後同步修正本樹、案件首頁、根目錄索引及受影響連結，勿在案件外另建同一內容。
