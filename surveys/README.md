# TVBS 站內問卷 Insight 報告

- `index.html`　問卷牆（所有問卷一覽）
- `reports/`　每份問卷的完整報告，各自是一個獨立網頁

## 上傳到 GitHub
1. 解壓縮，整個 `surveys` 資料夾直接拖進 GitHub 的 Add file → Upload files。
2. 檔名不要改，連結用相對路徑，改名會斷。
3. 開 GitHub Pages 後，網址是 `https://<帳號>.github.io/<repo>/surveys/`。

## 新增問卷
把新報告放進 `reports/`，再到 `index.html` 的 `window.__SURVEYS` 加一筆（或請 Claude 重新打包）。

## 備註
- 頁面裡沒有任何受訪者逐筆資料，只有算好的統計。
- 畫面是算好後存下來的，資料不會自動更新；圖表的滑鼠游標提示（hover）沒有保留。
