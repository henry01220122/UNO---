# UNO 規則大全

Homework 9：以 AGENTS.md 定義可持續擴充的規則知識網站。

## 使用方式
直接開啟 `index.html`。網站僅使用 HTML 與內嵌 CSS，沒有 Python 後端、JavaScript 套件、API 金鑰或安裝需求。

## 內容
基本玩法、功能牌圖鑑、特殊情境、計分方式、自訂玩法及資料來源。特殊情境可點擊展開。以經典 UNO 為基準，自訂玩法獨立標示。

## 架構
- index.html：全部網頁內容與樣式。
- AGENTS.md：分類、內容格式、視覺規範、查證與驗收流程。
- README.md：專案說明。

## 發布到 GitHub Pages
1. 在 GitHub 建立公開 Repository。
2. 上傳本資料夾的 index.html、AGENTS.md、README.md 到 Repository 根目錄，不是只上傳 ZIP。
3. Settings → Pages → Deploy from a branch → main → /(root) → Save。
4. 等待發布完成，複製 GitHub 顯示的網站網址，並用未登入的瀏覽器確認可讀取。
5. 將 Repository 與網站連結放進作業說明 Word，轉成 PDF；繳交 PDF 與 AGENTS.md。

上傳原始碼不代表網站已發布。請以 Pages 顯示的實際網址為準。

## 延伸方式
先讀 AGENTS.md，再新增規則。一般規則沿用 article.rule；爭議情境沿用 details.faq；自訂玩法一定標示 house rule。新增不同版本時建立獨立頁，不混入經典版。

## 來源與開發說明
規則參照 Mattel UNO 42001 與 B0001 官方說明書，連結位於網站資料來源區。繁體中文說明、版面與 CSS 示意卡牌由本專案整理製作，AI 協助開發；非 Mattel 官方網站。
延續先前 UNO 智慧裁判的主題，本次成果是靜態規則知識網站，不宣稱具備 Tool Use Agent 或完整牌局裁判能力。

## 提交前確認
公開網站可開啟；GitHub 內容齊全；AGENTS.md 與網頁對應；PDF 填入實際連結並說明如何擴充。網站已包含來源，不使用官方卡牌圖檔。
