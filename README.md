# 布丁的歌單

這是一個可部署到 GitHub Pages 的靜態歌單網站。

## 檔案

- `index.html`：網站主頁
- `style.css`：紫色系樣式
- `script.js`：讀取 Google 試算表與歌單功能

## 試算表欄位格式

請確認 Google 試算表權限設定為「知道連結的任何人可檢視」。

建議欄位：

- A 欄：歌名
- B 欄：歌手
- C 欄：分類
- D 欄：歌曲連結，可留空
- F 欄：標籤，可留空

## GitHub Pages 使用方式

1. 建立一個 GitHub repository。
2. 上傳 `index.html`、`style.css`、`script.js`。
3. 到 Settings → Pages。
4. Source 選擇 `Deploy from a branch`。
5. Branch 選擇 `main`，資料夾選 `/root`。
6. 儲存後等待 GitHub 產生網址。
