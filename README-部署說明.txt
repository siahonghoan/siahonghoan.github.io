# GitHub Pages 上線步驟

這份檔案包包含目前網站的最新版本，適用於 https://siahonghoan.github.io 。

1. 解壓縮 ZIP。
2. 開啟 GitHub 的 siahonghoan/siahonghoan.github.io 儲存庫。
3. 先備份目前儲存庫，或確認舊版本已在 Git 歷史中。
4. 選擇 Add file → Upload files，把本檔案包內的 index.html、publications.html、talks.html、conferences.html、style.css 和 .nojekyll 上傳到儲存庫根目錄。不要把整個外層資料夾上傳。
5. 選擇 Commit changes。若既有網站使用其他 CSS 或資產，不必刪除它們。
6. 到 Settings → Pages，確認 Source 為 Deploy from a branch，分支選 main（若你的預設分支是 master，選 master），資料夾選 / (root)，按 Save。若目前已使用 GitHub Actions 部署，請先確認既有流程，避免更改不相容的設定。
7. 等待 GitHub Pages 部署完成，開啟 https://siahonghoan.github.io 。若仍看到舊版，重新整理或清除快取。

網站內容：
- 首頁頂端保留泰文。
- 首頁標語為 Sound, structure & beyond.
- 主選單為 Home / Papers / Talks。
- Conferences 為獨立頁面，由 Talks 連入。
- 論文與演講頁均可搜尋。

這是靜態網站，不需要安裝套件、執行建置或使用 Sites 帳號。
