# case-90298156 證據保存與存取登記

舊編號60298156及CASE-2026-001均指本案。案件按使用者要求改用電話ID；原始來源檔名、EV編號及外部Drive名稱不改。共用規則見[證據及私隱規則](../../../EVIDENCE-STORAGE.md)。

## 外部Drive位置

既有受限資料位置如下，這是外部來源名稱，並非Git現行案件ID：

```text
Millie Beau Limited - Confidential Complaints/
  CASE-2026-001/
    01_WhatsApp/
    02_Contracts/
    03_Treatment_Records/
    04_Medical_Restricted/
    05_Legal/
    06_Evidence_Index/
```

[案件Drive資料夾](https://drive.google.com/drive/folders/1Qb65VrhNVwlrL_TXMrDnsbQetOivQDU7)維持Restricted權限，不因Git整理而更改共享或擁有者。

## 2026年10月11日來源保存記錄

- **已逐張保存 57 張獨立 JPG**（來源為本次對話提供的 JPEG，不能據此斷言為手機或其他裝置未經加工的原始檔），排除 AI 產生的縮圖、拼圖及培訓圖片。
- **上傳核對**：01_WhatsApp 44/44、02_Contracts 2/2、03_Treatment_Records 8/8、04_Medical_Restricted 3/3；無遺漏、無同名重複。四組 Drive JPG 檔案合共 **13,698,978 bytes**，與本地 57 張來源 JPG 總大小相符。
- [完整57張來源JPEG ZIP＋逐檔SHA-256清單](https://drive.google.com/file/d/1c74fsGWHm5muy3I9AwrSXzaYP6FBAih9/view)：Drive 受限檔案；ZIP SHA-256 `623ed7d394d632b652c4a8690303f9172e8653c0f89fd97c67cc91d8f57523b7`。
- [01_WhatsApp：44張來源JPEG ZIP](https://drive.google.com/file/d/1P_ntigJWmaGvKaCRCnPCv2VaU8Q_vZ2v/view)：44 張亦獨立存成 JPG，另有4本各11張的 Google Docs 圖像副本。
- [02_Contracts：2張來源JPEG ZIP](https://drive.google.com/file/d/1xr5jtNEZ1RcF8L7tYKjQCsXR-MRxFeNj/view)：2 張亦獨立存成 JPG，另有 Google Docs 閱覽副本。
- [03_Treatment_Records：8張來源JPEG ZIP](https://drive.google.com/file/d/1LXEsfAl9YC6LQaqQ90QwyjAbt3RVIL_U/view)：8 張亦獨立存成 JPG，另有 Google Docs 閱覽副本。
- [04_Medical_Restricted：3張來源JPEG ZIP](https://drive.google.com/file/d/15MgZVSFoMuQBwXMQbejgXAfJk-zFlo_p/view)：3 張來源 JPG 均有獨立檔案及 Google Docs 證據副本。
- **詳盡圖片索引**：[Google Docs Evidence Register](https://docs.google.com/document/d/17XK4Kld5P_WsVyRsuWYZOxR0aMPSmh_DU1FP4C_S3Cs/edit)。
- 所有受限資料夾經 Google Drive 權限中繼資料檢查為未共享、擁有者存取；仍需定期由公司覆核共享權限。
- 以上來源 JPEG 未經此輪處理修圖；但當初上傳本對話前可能經通訊程式壓縮或截圖，故不能以此證明最初裝置原始性。

## 本機受限資料

以下路徑以本案件資料夾為起點，整個`evidence/private-local/`排除Git，不在GitHub。

| 內容 | 本機路徑 |
| --- | --- |
| 醫學、對話及原圖逐項核對 | `evidence/private-local/restricted/medical-evidence-and-source-audit.md` |
| 57個來源成員的SHA-256清單 | `evidence/private-local/restricted/source-register.csv` |
| 來源工作副本、OCR及manifest | `evidence/private-local/source-work/` |
| 模型核查與重建支援 | `evidence/private-local/source-work/build_workbook.py` |
| 本次移動路徑及模型原雜湊 | `evidence/private-local/source-work/structure-migration.json` |

工作副本已移到本案資料夾；manifest中的本機路徑相應更新，原始圖片檔名及位元組照存。其他代理沒有本機檔案或外部存取時，記錄未取得，不能宣稱已閱原件。

## 仍需取得及後續保存

57張來源保存不等於取得當日激光／DCD、完整原帳、原生聊天、醫療機構病歷、後續康復或保單。具體缺口、負責角色及完成證明見[下一步](../actions/next-steps.md)。

新臨床資料及對話進入既有受控證據庫；Git只更新必要結論及狀態。公司批准或發送後，原始訊息、附件及送達證明另存受控資料，不把未發送草稿當作已發出。
