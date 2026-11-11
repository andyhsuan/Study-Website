# Studitude — 手寫筆記與讀書規劃

Studitude 的公開產品介紹網站。

**網站：** https://andyhsuan.github.io/Study-Website/

以實際 App 畫面、原創產品短片及示範資料介紹手寫筆記、PDF、AI 附件分享、讀書紀錄、課業規劃與隨手工具。

## 編輯與部署

這是靜態 HTML、CSS 與 JavaScript 網站，無需安裝套件或建置。

- `index.html`：頁面內容與搜尋／分享資訊
- `style.css`：桌機、平板與手機排版
- `app.js`：規劃分頁、圖片與影片視窗
- `assets/`：公開展示圖片與影片（目前短片為 21 秒、1080p、60 fps）
- `design/film.html`：產品短片的 Canvas 分鏡與動畫原始碼

GitHub Pages 使用 `main` 分支根目錄。推送更新後會自動發布；`.nojekyll` 保留靜態資源原貌。

本機可用 `python3 -m http.server 8792` 預覽。

App 程式碼、簽章與金鑰不在這個 repo。
