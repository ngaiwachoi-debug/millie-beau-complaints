# 新案件資料夾範本

案件ID用`case-<已核實並獲授權作識別的客戶電話>`。先查`CASE-INDEX.md`與舊編號，避免重複建檔；不要從含糊或錯誤編號猜電話。

```text
CASES/case-<phone>/
├── README.md                   現況及入口
├── AGENTS.md                   接手要點
├── TREE.md                     實際檔案樹
├── CASE.md                     使用案卷內容範本
├── actions/next-steps.md        結果、負責角色、日期及完成證明
├── responses/
│   ├── README.md               現行版本、批准及發送狀態
│   ├── YYYY-MM-DD.md            當日草稿
│   └── archive/                被取代的文字，勿直接發送
├── audit/YYYY-MM-DD/            當次研究及來源
├── financial/                  假設及模型
├── evidence/
│   ├── README.md               入口與缺口
│   ├── storage-and-access.md   受控來源與權限
│   └── private-local/          本機受限資料，不加入Git
└── archive/                    舊索引及歷史對照
```

只建立實際需要且有內容的檔案。沒有模型或研究時在案件首頁記錄未有，不以空白檔案暗示已完成。

建立後更新根目錄`CASE-INDEX.md`及`TREE.md`；所有案件內容留在該案件資料夾，根目錄只保存共用規則。原始證據、私密資料及未遮蓋收據不加入Git。案卷參照[投訴範本](COMPLAINT-CASE-TEMPLATE.md)。
