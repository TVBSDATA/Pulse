# TVBS 站內問卷 Insight 報告

- `index.html`　問卷牆（所有問卷一覽）
- `reports/`　每份問卷的完整報告，各自是一個獨立網頁

## 上傳到 GitHub
1. 解壓縮，整個 `surveys` 資料夾直接拖進 GitHub 的 Add file → Upload files。
2. 檔名不要改，連結用相對路徑，改名會斷。
3. 開 GitHub Pages 後，網址是 `https://<帳號>.github.io/<repo>/surveys/`。

## 先想一下再公開
- 頁面裡沒有任何受訪者逐筆資料，只有算好的統計。
- 問卷牆標示「內部使用」。貓狗報告含各版位 UU（來自內部流量）。public repo 或 Pages 任何人都看得到，內部用就放 private repo。

## 跟線上版的差別
- 畫面是算好後存下來的，資料不會自動更新；問卷有新回收要重新產生。
- 圖表的滑鼠游標提示（hover）沒有保留，數字都已標在圖上。
- 問卷牆的卡片是寫在 `index.html` 裡的 `window.__SURVEYS`，新增問卷就加一筆並放入 `reports/`。
