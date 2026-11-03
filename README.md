# 星空魔法學院｜互動故事

這是可直接部署到 GitHub Pages 的單頁 HTML 遊戲。

## 檔案
- `index.html`：遊戲主程式（含內嵌資源），可直接在瀏覽器開啟。
- `README.md`：專案說明與發布步驟。

## 本次更新
- 將 `20261101.html` 的角色配音設定整合至 `20261103.html`。
- 新增「配音模式」選單，預設為 **20261101** 角色配音模式；也可切換回 **20261103** 原有聲線模式。
- 國語／粵語選擇、角色語音、語音播放完成後自動播放下一句，以及 X1／X2／X3 速度同步設定皆保留。
- 保留原有遊戲內容、立繪、地圖、介面和自動播放功能。

## 本機預覽
直接以瀏覽器開啟 `index.html` 即可。建議使用最新版 Chrome 或 Edge。語音由瀏覽器的 Web Speech API 提供，實際可用聲線依作業系統／瀏覽器而異。

## 發布到 GitHub Pages
1. 在 GitHub 建立新的 Repository。
2. 將 `index.html` 和 `README.md` 上傳至 Repository 根目錄。
3. 開啟 Repository 的 **Settings → Pages**。
4. 在 **Build and deployment** 選擇 **Deploy from a branch**。
5. Branch 選 `main`，資料夾選 `/ (root)`，按 **Save**。
6. 等待部署完成後，從 Pages 顯示的網址開啟遊戲。

> 本專案為純靜態 HTML，不需要 Node.js、建置流程或伺服器端程式。
