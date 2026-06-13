# 🌿 九里飄香 - 桂花綜合學術與生活應用專題網
### Osmanthus: Academic & Lifestyle Application Web Project

> **大學生植物科普、在地創生與網頁前端互動之跨界專題研究**
> A Cross-Boundary Study on Botanical Science, Local Revitalization, and Web Front-End Interaction.

[![Live Demo](https://img.shields.io/badge/Live_Demo-GitHub_Pages-blue?style=for-the-badge&logo=github&logoColor=white)](https://su2006sgm.github.io/你的儲存庫名稱/)
![Tech Stack](https://img.shields.io/badge/Tech_Stack-HTML5%20%7C%20TailwindCSS%20%7C%20VanillaJS-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-Academic_Educational-green?style=for-the-badge)

本專案是一款基於網頁原生技術打造的**單頁式網頁應用程式（SPA）**。

專案核心進行了一場多維度的「自然科普與人文科技」縫合嘗試：將**桂花（Osmanthus）的學術辨識與科學栽培**，結合**彰化在地（鹿港桂花巷與田尾公路花園）的產業文化**，並導入網頁前端的互動技術。

觀看者可以透過此線上專題網，以數位互動方式深度探索桂花的四大品種群、在地文史脈絡、古法手作工藝，並體驗內建的智慧園藝輔助工具。

---

## 💡 內容架構與文化溯源 (Content & Cultural Context)

### 1. 學術辨識與科學管理
統整了四大名桂（金桂、銀桂、丹桂、四季桂）的特徵與香氣圖鑑，並針對春、夏、秋、冬四季，提供包含光照、水分、追肥與修剪的科學化管理指南。

### 2. 彰化在地創生連結
* **鹿港桂花巷藝術村**：探討清治時期貿易河道旁的桂花歷史底蘊，以及現今轉型為藝術進駐基地的文化地標意義。
* **田尾公路花園**：連結全台最大花卉集散地，介紹具備百年歷史的園藝產業鏈與桂花故鄉的實力。

### 3. 古典詩詞與手作工藝轉譯
將古典詩詞（如王維、李清照之作）中的「蟾宮折桂」意境，延伸至現代生活應用。透過網頁互動介面，解析傳統窨製桂花茶、古法醃漬桂花蜜、桂花酒與精油提煉的嚴謹製程。

---

## 🛠️ 技術亮點與核心功能 (Tech Highlights)

本專案完全採用**原生 Web 技術**打造，捨棄厚重的框架，針對以下前端領域進行深度實作：

### ✨ 核心互動技術
* **🩺 病蟲害智慧診斷模擬系統 (Simulated Diagnostics)**
    預載常見病徵物件資料庫（如炭疽病、煤煙病、介殼蟲等）。利用原生 JavaScript 邏輯，讓使用者透過選取植物外觀症狀，系統即時比對並動態渲染出對應的分類標籤、嚴重度與專業防治指引。
* **📔 無後端栽培日誌 (Local Storage State Management)**
    不依賴後端伺服器，直接實作 **Web Storage API (LocalStorage)**。使用者可以在瀏覽器端安全地新增、瀏覽與清除個人專屬的植物栽培紀錄，展現前端狀態管理與資料持久化的能力。

### ✨ UI/UX 特色系統
* **🎨 現代化響應式設計 (RWD & Custom Theme)**
    全面導入 Tailwind CSS，客製化專案專屬的 `gold` 與 `forest` 主題色系配置。搭配 `backdrop-blur` 頂部導覽列與平滑滾動（Smooth Scrolling）機制，完美適配行動裝置與桌機。
* **⚡ 客製化微互動 (Micro-interactions)**
    自主開發輕量級的 UI 元件，包含時間驅動的 Toast 系統通知（如「日記儲存成功！」），以及運用 DOM 操作實現的手風琴式（Accordion）DIY 工法折疊選單。

---

## 📂 檔案結構 (Structure)

本專案採用高度整合的單頁面架構，無需額外建置環境，便於部屬與維護：

```plaintext
├── index.html          # 專題網主程式碼（包含完整 HTML 結構、Tailwind 配置與 JS 邏輯）
└── README.md           # 本說明文件
