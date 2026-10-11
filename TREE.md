# 儲存庫目錄樹

根目錄提供導覽和共用規則，案件內容集中在一個資料夾。完整檔案及用途見[case-90298156目錄樹](CASES/case-90298156/TREE.md)。

```text
millie-beau-complaints/
├── README.md                         案件庫首頁
├── AGENTS.md                         代理工作指引
├── CASE-INDEX.md                     現行ID、電話及舊編號索引
├── TREE.md                           本目錄
├── EVIDENCE-STORAGE.md               共用證據及私隱規則
├── .gitignore                        敏感原件及本機副本排除規則
├── CASES/
│   └── case-90298156/
│       ├── README.md                 案件入口與現況
│       ├── AGENTS.md                 本案接手指引
│       ├── TREE.md                   本案完整目錄
│       ├── CASE.md                   現行案卷
│       ├── actions/                  結果與待辦
│       ├── responses/                現行草稿、狀態及舊回覆
│       ├── audit/2026-10-11/         完整管理層研究
│       ├── financial/                模型與使用說明
│       ├── evidence/                 外部證據存取登記
│       │   └── private-local/        本機受限副本，不在GitHub
│       └── archive/                  舊索引，僅作歷史對照
└── TEMPLATES/
    ├── CASE-FOLDER-TEMPLATE.md        新案件結構範本
    └── COMPLAINT-CASE-TEMPLATE.md     案卷內容範本
```

`private-local/`只在本機存在，不是GitHub附件。原始Drive資料夾及檔名維持既有名稱。

## 舊路徑對照

| 舊路徑 | 現行位置 |
| --- | --- |
| `CASES/60298156.md` | [案卷](CASES/case-90298156/CASE.md) |
| `CASES/CASE-2026-001.md` | [舊索引](CASES/case-90298156/archive/legacy-case-index.md) |
| `ACTIONS/60298156-next-steps.md` | [下一步](CASES/case-90298156/actions/next-steps.md) |
| `RESPONSES/60298156-2026-10-13-revised.md` | [13日草稿](CASES/case-90298156/responses/2026-10-13.md) |
| `RESPONSES/CASE-2026-001-replies.md` | [舊回覆](CASES/case-90298156/responses/archive/CASE-2026-001-replies.md) |
| `AUDITS/2026-10-11/` | [審核索引](CASES/case-90298156/audit/2026-10-11/README.md) |
| `outputs/legal-audit-2026-10-11/exposure-model.xlsx` | [模型](CASES/case-90298156/financial/exposure-model.xlsx) |
| 舊`EVIDENCE-STORAGE.md`的個案部分 | [案件證據登記](CASES/case-90298156/evidence/storage-and-access.md) |

舊提交中的檔案仍可由Git歷史查閱；目前資料只從新案件入口維護。
