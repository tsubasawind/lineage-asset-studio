# Lineage Asset Studio

純前端的本機 Lineage 素材整理工具，使用原生 HTML、CSS、JavaScript 與 File System Access API。

## 使用方式

1. 使用最新版 Chrome 或 Edge 開啟 `index.html`。
2. 選擇 `LineageAssets` 根資料夾並授權讀寫。
3. 索引、分類、設定與備份會儲存在素材根目錄下的 `.LineageAssetStudio`。

## 專案檔案

- `index.html`
- `style.css`
- `app.js`
- `README.md`
- `.gitignore`

素材圖片、`LineageAssets` 及 `.LineageAssetStudio/backups` 不應提交至 Git。

## 備份

工具會在每 100 次批次分類，以及專案變更滿 30 分鐘時建立快照；也可手動建立。最多保留最近 20 個自動快照。還原前會先建立 emergency backup。
