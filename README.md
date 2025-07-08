# 轉轉小瑪莉 抽獎系統

## 架構
- **後端**：Google Apps Script (`src/Code.gs`)
- **前端**：LIFF + `html/index.html`、`html/query.html`
- **樣式**：`static/css/style.css`

## 本地開發
1. 安裝 Clasp：`npm install -g @google/clasp`
2. `clasp login`
3. `clasp clone <Script ID>`
4. 開發並 `clasp push`

## 自動部署
Push 到 `main` 分支後，GitHub Actions 自動執行部署。

## 使用方式
- 抽獎頁面：`https://liff.line.me/<LIFF_ID>/index.html?storeId=S001`
- 查詢頁面：`https://liff.line.me/<LIFF_ID>/query.html?storeId=S001`
