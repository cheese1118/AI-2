# 深宮秘檔・侍寢錄 PWA

## 上傳 GitHub Pages
1. 建立一個 GitHub repository。
2. 上傳本資料夾所有檔案：`index.html`、`manifest.json`、`service-worker.js`、`icons/`。
3. 到 Settings → Pages，選擇 Branch：`main`，資料夾選 `/root`。
4. 等 GitHub Pages 產生網址後，用手機 Safari / Chrome 打開。
5. iPhone：分享 → 加入主畫面。Android：瀏覽器選單 → 安裝 App / 加到主畫面。

## 資料隱私
本版是手機單機匯入版：沒有伺服器 API、沒有 fetch、沒有 localStorage。匯入的 JSON 只在當次瀏覽器頁面記憶體中使用。重新整理後需要重新匯入。

注意：你把 HTML/PWA 程式上傳到 GitHub Pages，公開的是「程式本身」。你匯入的 21 人 JSON 不會被這個 PWA 自動上傳到 GitHub 或網路，除非你自己把 JSON 檔也上傳到 repository，或把資料貼到程式碼裡。
