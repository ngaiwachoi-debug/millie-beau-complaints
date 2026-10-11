# 機密證據儲存指引（不在 GitHub 保存原件）

## 分工
- GitHub：經去識別化的個案概述、風險分析、待辦、回覆草稿及處理進度。
- Google Drive / 公司受控文件庫：原始WhatsApp截圖／匯出、已簽合約、付款單、操作紀錄、傷勢照片、醫療文件及完整通信紀錄。

## 建議 Google Drive Folder
```
Millie Beau Limited - Confidential Complaints/
  CASE-2026-001/
    01_WhatsApp/
    02_Contracts/
    03_Treatment_Records/
    04_Medical_Restricted/
    05_Legal/
    06_Evidence_Index/
```

## 保存與存取
1. 機密資料夾設 Restricted；只限直接負責個案的管理層、授權法律顧問，醫療照片採更嚴格子資料夾權限。切勿用 Anyone with the link。
2. 公司統一擁有檔案，避免由員工個人Google帳戶保存；開啟雙重認證，審閱共享名單與存取日誌。
3. 保留原件，不裁改、覆蓋或刪除；另建需要分享的遮蓋版。保留原始檔案時間、來源、接收日期及核實狀態。
4. 原始醫療／私密照片不放在 GitHub、Issue、PR、README、commit 或 Git history；.gitignore 不是外洩防護，仍須人手檢查上傳內容。
5. GitHub 個案只記錄資料庫內的**不含身份資訊的證據編號**及存取負責人；如需連結，只供已授權人員在受控系統內使用。
6. 如涉及訴訟預期，立即暫停例行刪檔並徵詢法律顧問；保留期由公司依法律責任與必要性制定。
7. 客戶要求查閱個人資料，需另按香港適用的個人資料私隱程序處理。

## CASE 60298156：已完成圖片保存（2026-10-11）
- [Google Drive CASE 資料夾](https://drive.google.com/drive/folders/1Qb65VrhNVwlrL_TXMrDnsbQetOivQDU7)；由於內容有醫療和個資，勿設為 Anyone with the link。
- [完整 57 張來源 JPEG ZIP](https://drive.google.com/file/d/1c74fsGWHm5muy3I9AwrSXzaYP6FBAih9/view)（附逐檔 SHA-256 清單；檔案來源為聊天可取得的 JPG）。
- **所有 57 張來源 JPG 都已作為單獨圖片上傳對應 Drive 子資料夾**：WhatsApp 44 張、合約 2 張、療程系統 8 張、醫療文件 3 張。除獨立 JPG 外，各組亦有分類 ZIP；WhatsApp、合約及療程有 Google Docs 可閱覽副本，醫療三張亦有 Google Docs 證據副本。經完整資料夾清單核對，各組無遺漏及無同名重複。
- [完整保存索引](https://docs.google.com/document/d/17XK4Kld5P_WsVyRsuWYZOxR0aMPSmh_DU1FP4C_S3Cs/edit) 記錄來源分組、Google Drive 位置及核查結果。
- 檔案已核對來源數量及 Drive 單獨 JPG 檔案大小：57 張合共 **13,698,978 bytes**，與本地來源檔案總大小一致；照片本身可能早於本次保存已由截圖或訊息平台處理，毋須將其宣稱為裝置拍攝未處理的原檔。

## 案件研究與後續資料

- 來源核查結果、仍缺的原始資料及下一步分工，見[目前結果與下一步](ACTIONS/60298156-next-steps.md)。完成57張來源保存不等於已取得完整原生聊天、當日設備／DCD、醫療機構病歷、後續康復或保單。
- 醫學逐項核對、來源雜湊及敏感工作副本只保存在本機受限附錄與受控證據流程；`outputs/restricted/`及`outputs/local-only-evidence/`排除Git追蹤。
- GitHub的財務工作簿只含明示計劃假設及公開判例，不填客戶身分或詳細病歷。新臨床文件、原對話及付款憑證仍送入受控資料庫，GitHub只更新必要的去識別化結論。
- 批准及實際對外發送後，將原始發送副本、附件和送達紀錄另行保存；未發送的草稿不放進「已發出」紀錄。
