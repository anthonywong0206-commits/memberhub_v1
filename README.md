# MemberHub 會員管理系統｜靜態版 v2.1 輸入修復版

## 修復內容
- 修復文字欄輸入時不能正常打字的問題
- 表格輸入不再每打一個字就重新渲染整個頁面
- 出生日期仍會自動計算年齡
- 保留 localStorage 儲存、會員管理、搜尋、列印/PDF、Word 匯出、設定功能

## GitHub Pages 安裝方法
1. 解壓 ZIP。
2. 將 `index.html`、`style.css`、`app.js` 上載到 GitHub repo 根目錄。
3. 到 repo 的 Settings → Pages。
4. Source 選 `Deploy from a branch`。
5. Branch 選 `main`，Folder 選 `/root`。
6. Save 後等 1–3 分鐘。

## Vercel 安裝方法
1. Import GitHub repo。
2. Framework Preset 選 `Other`。
3. Build Command 留空。
4. Output Directory 留空。
5. Deploy。

## 注意
不要上載 `node_modules`，亦不需要 `npm install`。
