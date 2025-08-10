# 互耶室內裝修設計｜無障礙空間設計需求表（GitHub Pages）

這是可直接部署在 **GitHub Pages** 的單頁表單。適合在 LINE 對話中貼連結給客戶，客戶點開即可勾選並產生摘要回貼。

## 部署步驟
1. 建立新 Repo（或使用既有 Repo）。
2. 把 `index.html` 放到 Repo 根目錄。
3. 到 **Settings → Pages**：
   - Source 選擇 `Deploy from a branch`
   - Branch 選擇 `main` 與 `/root`，按 **Save**
4. 片刻後會得到網址，例如 `https://<你的帳號>.github.io/<repo-name>/`。
5. 把網址貼到 LINE，客戶即可使用。

## 客製化
- LOGO：目前使用 data URL 內嵌，直接在 `index.html` 頂端的 `logo_data_url` 部分替換即可。
- 顏色：CSS 變數在 `:root` 定義（粉紫、橘黃、淡黃）。
