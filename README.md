# 公車路線測驗

純靜態網頁（單一 `index.html`），使用 TDX 公共運輸資料 + Leaflet 地圖。

## 部署到 GitHub Pages
1. 在 GitHub 建立新 repo（例如 `bus-quiz`）
2. 把 `index.html`、`README.md` 上傳到 repo
3. Settings → Pages → Source 選 `Deploy from a branch`，Branch 選 `main` / `(root)` → Save
4. 約 1 分鐘後即可用 `https://<你的帳號>.github.io/bus-quiz/` 開啟

## 使用
- 先到「設置」輸入 TDX Client ID / Secret（存在瀏覽器 localStorage，不會上傳）
- 「開始」→ 選縣市、輸入路線（如 `19A`、`6700~6710`）→ 開始

## 路線名稱比對
- `19A` ⇄ TDX 的 `19路A`（去掉「路」、括號備註、空白、大小寫）
- 不標主/副時，`6700` 會同時包含 `6700`、`6700主`、`6700副`
- `6700~6710` 以數字主線號範圍篩選
