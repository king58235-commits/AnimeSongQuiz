動畫猜歌主持台－外部題庫版

檔案：
- index.html：工具本體
- quiz-data.json：正式題庫

部署到 GitHub Pages：
1. 將 index.html 與 quiz-data.json 上傳到同一個 repository 根目錄。
2. 啟用 GitHub Pages。
3. 手機透過 GitHub Pages 網址開啟。

更新題庫：
1. 在網站內新增、刪除、編輯題目。
2. 到「匯入／備份」按「匯出完整題庫 JSON」。
3. 下載的檔案名稱就是 quiz-data.json。
4. 到 GitHub 覆蓋舊的 quiz-data.json。
5. 其他裝置重新整理網站後即可讀到新版題庫。

注意：
- 編輯中的內容仍會先存成該瀏覽器的本機草稿。
- 「重新載入外部題庫」會放棄該瀏覽器的本機草稿，重新讀取 GitHub 上的 quiz-data.json。
- index.html 不再內建329題；完整題庫只存在 quiz-data.json。
