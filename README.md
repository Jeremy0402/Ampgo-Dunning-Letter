# AmpGO 催款信產生器

線上開啟：https://jeremy0402.github.io/Ampgo-Dunning-Letter/

填入欄位、預覽信件內容，按「複製信件」貼到 Gmail 寄出。資料只存在你自己瀏覽器的 localStorage，不會上傳到任何伺服器。

## Logo 圖片

把 Logo 檔案放進 `assets/logo.png`（或改成別的檔名，並同步修改 `index.html` 裡 `logoUrl` 的預設值），推送到 GitHub 後即可透過以下網址公開讀取：

```
https://cdn.jsdelivr.net/gh/Jeremy0402/Ampgo-Dunning-Letter@main/assets/logo.png
```

用 jsdelivr 而不是直接用 GitHub 網址，是因為它是專門設計給網站/信件公開引用圖片的 CDN，速度快、穩定，不會有 GitHub 本身對外連結圖片時可能出現的限制或延遲問題。

## 修改內容/樣式

直接在 GitHub 網頁上編輯 `index.html`，或把網址開頭的 `github.com` 換成 `github.dev`（例如 `github.dev/Jeremy0402/Ampgo-Dunning-Letter`）用線上編輯器修改，存檔（Commit）後幾秒內網站就會更新。
