# Xbox Cloud Gaming 優化整合

Xbox Cloud Gaming 的使用者腳本，適用於 Tampermonkey、Violentmonkey 等相容的使用者腳本管理器。

> 本專案為既有 Xbox Cloud Gaming 優化整合腳本的後續維護版本。請僅從可信任的發布來源安裝，並自行評估使用風險。

## 安裝

1. 在瀏覽器安裝使用者腳本管理器，例如 [Tampermonkey](https://www.tampermonkey.net/) 或 [Violentmonkey](https://violentmonkey.github.io/)。
2. 目前正式安裝與更新來源仍為 Greasy Fork：
   [安裝 Xbox Cloud Gaming 優化整合腳本](https://update.greasyfork.org/scripts/588851/Xbox%20Cloud%20Gaming%E4%BC%98%E5%8C%96%E6%95%B4%E5%90%88.user.js)
3. 依使用者腳本管理器顯示的提示完成安裝。

## 適用網站

腳本目前宣告的比對網址如下：

- `https://www.xbox.com/*/*play*`
- `https://www.xbox.com/*/play*`
- `https://play.xbox.com/*`

## 版本

目前匯入版本：`1.0.3`。

詳細變更請參閱 [CHANGELOG.md](CHANGELOG.md)。

## 發布與更新策略

- **GitHub**：保存原始碼、文件與版本歷史。
- **Greasy Fork**：目前的正式使用者安裝與更新來源。

現有腳本中 `@downloadURL` 與 `@updateURL` 仍指向 Greasy Fork；本次首次提交不會改動腳本執行邏輯或既有更新渠道。若日後要改為 GitHub 發布更新，應在修改腳本中繼資料、測試更新流程後再進行。

## 致謝與授權注意事項

本腳本的中繼資料標示為 `MIT`，並保留了 `better-xcloud` 的 MIT 授權聲明。專案公開維護時，請持續保留所有上游專案的著作權與授權通知。

本倉庫尚未另行新增專案根目錄的 `LICENSE` 檔案；在確認所有整合程式碼的來源與授權相容性前，不應將未核實的整體授權狀態視為已確認結論。

## 回報問題

請在本倉庫的 [Issues](https://github.com/darkchaox/xbox-cloud-gaming-optimizer/issues) 提供：

- 瀏覽器與版本；
- 使用者腳本管理器及版本；
- 操作步驟與預期結果；
- 可重現問題的畫面、主控台錯誤或其他必要資訊。

請勿在 Issue 中提交帳號密碼、Cookie、權杖或其他敏感資料。
