# 隱私權聲明
最近更新日期：2025-03-15

## 1. 簡介
感謝您使用 Google Apps Connector for n8n（以下簡稱「本應用」）。我們重視您的隱私，並致力於保護您的個人資料安全。本隱私權聲明說明我們如何存取、使用和保護您的資料，並符合 Google API 服務用戶資料政策。

## 2. 我們收集的資訊
本應用不會存儲您的任何個人資料或 Google 服務內容。我們僅透過 Google API 讀取、處理並即時傳輸必要資訊，以執行自動化工作流。

我們存取以下 Google 服務的資料，並根據您的授權執行操作：

|應用|權限|用途|
|--|--|--|
|Gmail|https://mail.google.com/（完整 Gmail 存取權） <br>.../auth/gmail.modify（讀取、撰寫及標記 Gmail 郵件） <br>.../auth/gmail.compose（管理草稿和傳送電子郵件）|讀取 Gmail 郵件以進行內容分析，並產生建議回覆。<br>透過 n8n 自動化流程 建立 Gmail 草稿或發送郵件（需使用者確認）。<br>標記郵件，例如「已處理」或「待回覆」，幫助管理郵件工作流。|
|Google Sheets|.../auth/spreadsheets（讀取、寫入及管理 Google Sheets）|將分析結果寫入 Google Sheets 以作為記錄或報告用途。<br>自動更新表格內容，無需手動輸入。|
|Google Drive Labels|.../auth/drive.labels（查看、編輯、建立及刪除 Google 雲端硬碟標籤） <br>.../auth/drive.labels.readonly（查看 Google 雲端硬碟標籤）<br>.../auth/drive.admin.labels（管理 Google Workspace 組織內的標籤）|為 Google Sheets 文件自動加入標籤，提升檔案分類與搜尋效率。<br>確保 Google Workspace 內的標籤管理符合企業標準。|


## 3. 我們如何使用您的資料
我們僅在您的授權範圍內存取和處理資料，所有操作均透過 Google API 直接執行，不會將任何資料存儲於本應用或伺服器上。我們的主要用途包括：

自動化處理 Gmail 郵件（回覆、標記或歸檔郵件）。
寫入 Google Sheets 以記錄分析結果。
管理 Google Drive 文件標籤 以提升組織管理效率。

## 4. 資料安全與保護
我們採取以下措施確保您的資料安全：

即時存取，不做任何資料數據儲存：所有資料處理均即時進行，不會儲存您的 Gmail、Google Sheets 或 Google Drive 內容。
僅存取必要權限：我們僅請求執行工作流所需的最小權限。

使用 Google 授權機制：我們透過 OAuth 2.0 進行身份驗證，不會收集或存儲您的 Google 密碼。
關於用戶控制：您可隨時在 Google 帳戶安全設置 中撤銷對本應用的授權。

## 5. 第三方分享
本應用不會與任何第三方共享您的個人資料或 Google 服務內容。所有資料均透過 Google API 直接傳輸，確保安全性與隱私保護。

## 6. 使用者控制與權限管理
您可以在 Google 帳戶中隨時撤銷或管理應用程式的權限：

進入 Google 安全性設定。
在「第三方應用程式存取權限」中，找到本應用並選擇「移除存取權」。

## 7. 變更隱私權政策
我們可能會根據應用功能或法規要求更新本隱私權聲明。如有重大變更，我們將在應用內或透過其他管道通知您。請定期查閱本頁以了解最新資訊。

## 8. 聯絡我們
如有任何問題或隱私權相關需求，請聯繫我們：
📧 聯絡信箱：kedych@gmail.com

