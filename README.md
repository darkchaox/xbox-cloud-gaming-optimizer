# Xbox Cloud Gaming 優化整合

Xbox Cloud Gaming 使用者腳本，提供**地區限制處理**、串流資訊顯示、畫面與控制調整等常用功能。

[**立即安裝最新版本**](https://raw.githubusercontent.com/darkchaox/xbox-cloud-gaming-optimizer/main/Xbox-Cloud-Gaming-Optimizer.user.js)　|　[Greasy Fork 安裝頁](https://update.greasyfork.org/scripts/588851/Xbox%20Cloud%20Gaming%E4%BC%98%E5%8C%96%E6%95%B4%E5%90%88.user.js)

> 本專案免費提供。請僅從本 GitHub 倉庫或 Greasy Fork 取得腳本，勿相信任何付費販售或來路不明的轉載版本。

## 主要功能

- **解除地區限制**：提供免代理直連、選服與自訂 IP 等設定，用於協助處理 Xbox Cloud Gaming 的地區限制。
- **串流資訊顯示**：可查看幀率、延遲、碼率、解析度等串流資訊。
- **畫面與串流調整**：提供 720P／1080P、瀏覽器編解碼偏好、畫面比例及亮度、對比、飽和度、清晰度等選項。
- **操作體驗調整**：提供自動全螢幕、觸控控制顯示與屏蔽等設定。
- **其他常用設定**：提供遊戲語言、IPv6 優先、網路檢測與實體伺服器相關選項。

實際可用功能會因瀏覽器、裝置、網路環境、帳號權限及 Xbox 服務狀態而不同，請以設定面板中顯示的選項為準。

## 設定面板預覽

![Xbox Cloud Gaming 優化整合的設定面板](assets/settings-panel.png)

設定面板可在 Xbox Cloud Gaming 頁面中開啟；請先從預設值開始，並在每次調整後確認串流與控制是否正常。

## 安裝方式

### 1. 安裝使用者腳本管理器

請先在瀏覽器安裝任一相容的使用者腳本管理器：

- [Tampermonkey](https://www.tampermonkey.net/)
- [Violentmonkey](https://violentmonkey.github.io/)

### 2. 安裝腳本

點擊 [**立即安裝最新版本**](https://raw.githubusercontent.com/darkchaox/xbox-cloud-gaming-optimizer/main/Xbox-Cloud-Gaming-Optimizer.user.js)，並依腳本管理器顯示的提示確認安裝。

### 3. 開啟 Xbox Cloud Gaming

前往下列任一網址並啟動遊戲：

- `https://www.xbox.com/play`
- `https://play.xbox.com/`

腳本會在符合條件的 Xbox Cloud Gaming 頁面中載入。

## 使用建議

1. 先以預設設定進入遊戲，確認串流與控制正常。
2. 如有地區可用性問題，可嘗試依序調整「免代理直連」、「選服」或「自訂 IP」等選項。
3. 如要調整畫面或串流表現，建議一次只改變一項設定，方便判斷效果。
4. 如出現畫面、聲音、控制或連線異常，請將最近修改的選項恢復預設後重新整理頁面。

## 使用前請注意

- 本腳本不提供 Xbox Game Pass、雲端遊戲資格、遊戲內容或網路服務。
- 地區可用性、畫質、延遲與穩定性會受到帳號、網路、裝置、瀏覽器、服務區域及 Xbox 服務狀態影響；本腳本不保證任何特定環境都能成功解除限制或改善體驗。
- 請遵守你所在地區適用的法律，以及 Microsoft／Xbox 的服務條款。
- 腳本目前的正式更新來源為 Greasy Fork；GitHub 用於公開原始碼、文件與最新維護內容。

## 常見問題

### 安裝後沒有作用，怎麼辦？

請依序檢查：

1. Tampermonkey 或 Violentmonkey 是否已啟用；
2. 腳本是否在管理器中處於啟用狀態；
3. 目前頁面是否為 `xbox.com/play` 或 `play.xbox.com`；
4. 重新整理 Xbox Cloud Gaming 頁面後再測試；
5. 暫時停用其他可能修改 Xbox 網頁的擴充功能後再測試。

### 為什麼調整後沒有改善延遲或畫質？

串流表現同時受網路、裝置效能、瀏覽器編解碼能力、服務區域與 Xbox 伺服器狀態影響。腳本提供的是調整選項與資訊輔助，無法保證任何網路環境一定改善。

## 回報問題

請到 [GitHub Issues](https://github.com/darkchaox/xbox-cloud-gaming-optimizer/issues) 回報問題，並盡量提供：

- 瀏覽器、作業系統與使用者腳本管理器版本；
- 問題發生步驟、預期結果與實際結果；
- 可公開的錯誤訊息或畫面截圖。

請勿提交帳號密碼、Cookie、Token、個人資料或其他敏感資訊。

## 致謝

本專案**並非從零開發的原創腳本**。現行版本以 **奈非天** 整理與分享的 Xbox Cloud Gaming 優化整合腳本為基礎，進行後續維護與優化。

感謝 **better-xcloud** 專案，以及 **奈非天** 過去的開發、整理與分享。相關上游程式碼的著作權與授權聲明已保留於原始碼中；詳情請參閱 [NOTICE.md](NOTICE.md)。

## 版本紀錄

請參閱 [CHANGELOG.md](CHANGELOG.md)。
