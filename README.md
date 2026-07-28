# Xbox Cloud Gaming 優化整合

> Xbox Cloud Gaming 使用者腳本，提供**地區限制處理**、串流資訊顯示，以及畫面與操作體驗調整。

[**立即安裝最新版**](https://raw.githubusercontent.com/darkchaox/xbox-cloud-gaming-optimizer/main/Xbox-Cloud-Gaming-Optimizer.user.js)　｜　[**Greasy Fork 安裝頁**](https://greasyfork.org/zh-CN/scripts/588851-xbox-cloud-gaming%E4%BC%98%E5%8C%96%E6%95%B4%E5%90%88)　｜　[**回報問題**](https://github.com/darkchaox/xbox-cloud-gaming-optimizer/issues)

本專案免費提供。請僅從本 GitHub 倉庫或 Greasy Fork 取得腳本，勿相信任何付費販售或來路不明的轉載版本。

## 這個腳本可以做什麼？

- **處理地區限制**：提供免代理直連、選服與自訂 IP 等選項，用於協助處理 Xbox Cloud Gaming 的地區限制。
- **掌握串流狀態**：顯示幀率、延遲、碼率與解析度等資訊，便於判斷串流情況。
- **調整畫面與編解碼**：提供 720P／1080P、瀏覽器編解碼偏好、畫面比例，以及亮度、對比、飽和度與清晰度調整。
- **改善操作體驗**：提供自動全螢幕、觸控控制顯示與屏蔽等選項。
- **提供常用進階設定**：包含遊戲語言、IPv6 優先、網路檢測與實體伺服器相關選項。

實際可用功能會因帳號權限、服務區域、瀏覽器、裝置與網路環境而異；請以遊戲頁面中的設定面板為準。

## 設定面板預覽

![Xbox Cloud Gaming 優化整合設定面板](assets/settings-panel.png)

## 快速開始

### 1. 安裝使用者腳本管理器

請先在瀏覽器安裝任一相容的使用者腳本管理器：

- [Tampermonkey](https://www.tampermonkey.net/)
- [Violentmonkey](https://violentmonkey.github.io/)

### 2. 安裝腳本

點擊 [**立即安裝最新版**](https://raw.githubusercontent.com/darkchaox/xbox-cloud-gaming-optimizer/main/Xbox-Cloud-Gaming-Optimizer.user.js)，並在腳本管理器的安裝頁確認安裝。

### 3. 開啟 Xbox Cloud Gaming

前往下列任一網址並啟動遊戲：

- `https://www.xbox.com/play`
- `https://play.xbox.com/`

進入遊戲後，開啟腳本設定面板，先使用預設值確認串流與控制正常，再依需求調整選項。

## 使用建議

1. **優先處理地區可用性**：如有地區限制問題，可依序嘗試「免代理直連」、「選服」與「自訂 IP」選項。
2. **一次只調整一項**：修改解析度、編解碼偏好或畫面設定後，請觀察是否影響畫面、聲音、輸入與連線。
3. **異常時回復預設**：若出現黑畫面、控制異常、聲音問題或無法連線，請先還原最近變更的選項並重新整理頁面。
4. **保留設定紀錄**：在更新腳本前，若有重要自訂配置，建議先記錄目前選項。

## 使用前請注意

- 本腳本不提供 Xbox Game Pass、雲端遊戲資格、遊戲內容或網路服務。
- 地區可用性、畫質、延遲與穩定性受到帳號、裝置、網路、瀏覽器、服務區域及 Xbox 服務狀態影響；本腳本不保證任何環境均可解除限制或改善體驗。
- 請遵守你所在地區適用的法律，以及 Microsoft／Xbox 的服務條款。
- GitHub 保存原始碼、文件與問題回報；Greasy Fork 為正式安裝與自動更新渠道。

## 常見問題

### 安裝後沒有作用，怎麼辦？

請依序確認：

1. Tampermonkey 或 Violentmonkey 已啟用；
2. 腳本在管理器中處於啟用狀態；
3. 目前頁面為 `xbox.com/play` 或 `play.xbox.com`；
4. 已重新整理 Xbox Cloud Gaming 頁面；
5. 已暫時停用其他可能修改 Xbox 網頁的擴充功能。

### 為什麼調整後沒有改善延遲或畫質？

串流表現同時受網路品質、裝置效能、瀏覽器編解碼能力、服務區域與 Xbox 伺服器狀態影響。腳本提供的是調整選項與資訊輔助，無法保證所有網路環境都能改善。

## 問題回報

請在 [GitHub Issues](https://github.com/darkchaox/xbox-cloud-gaming-optimizer/issues) 回報問題，並盡量附上：

- 瀏覽器、作業系統與腳本管理器版本；
- 重現問題的步驟、預期結果與實際結果；
- 可公開的錯誤訊息或畫面截圖。

請勿提交帳號密碼、Cookie、Token、個人資料或其他敏感資訊。

## 致謝

本專案**並非從零開發的原創腳本**。現行版本以 **奈非天** 整理與分享的 Xbox Cloud Gaming 優化整合腳本為基礎，進行後續維護與優化。

感謝 **better-xcloud** 專案，以及 **奈非天** 過去的開發、整理與分享。相關上游程式碼的著作權與授權聲明已保留於原始碼中；詳情請參閱 [NOTICE.md](NOTICE.md)。

## 版本紀錄

請參閱 [CHANGELOG.md](CHANGELOG.md)。
