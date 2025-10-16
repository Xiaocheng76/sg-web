# 我的作品網頁 (示範專案)

包含:
- index.html: 網頁主檔案
- styles.css: 樣式
- script.js: JavaScript (canvas 統計圖)
- README.md: 部署與修改說明

## 部署快速教學

### 1) 使用 GitHub Pages
1. 建立 GitHub repository，將本專案 push 到 repo。
2. 在 repo > Settings > Pages 選擇部署來源 'main' branch 和 `/ (root)`。
3. 幾分鐘後即可透過 `https://<your-username>.github.io/<repo-name>/` 存取。

### 2) 使用 Netlify (拖放)
1. 前往 netlify.com 登入，使用「New site from Git」或直接拖放 zip。
2. 指定 build 命令（靜態站通常不需要），部署即可取得網址。

### 3) 本機測試
在 project 目錄啟動簡單伺服器：
- Python 3: `python -m http.server 8000`
然後在瀏覽器開啟 `http://localhost:8000`

## 替換同學連結
請打開 index.html，把 <a> 的 href 換成您班上三位同學實際的網站網址。

