# 專案架構說明 (Project Architecture Description)

這是一個包含多個展示應用程式的入門展示網頁專案。

## 目錄結構 (Directory Structure)

- `index.html` : 專案首頁（主選單），提供前往各個展示應用的入口。
- `common/` : 共用檔案區，存放各種展示頁面皆需使用的資源。
  - `style.css` : 全局共用的 CSS 樣式表（設計系統、顏色定義、排版及美觀的深色主題）。
  - `script.js` : 全局共用的 JavaScript 腳本（共用邏輯或全域配置）。
- `apps/` : 依內容分類的不同程式（各別功能模組區）。
  - `hello-world.html` : Hello World 展示網頁。
  - `multiplication.html` : 99 乘法表展示網頁。
  - `grade-system.html` : 學生成績登入系統展示網頁。
  - `ai-news.html` : AI 財經新聞 Agent 展示網頁。

## 專案功能模組 (Features)

1. **Hello World**: 最基礎的網頁展示，包含高質感的漸層文字與動態效果。
2. **99乘法表**: 使用 JavaScript 動態產生，具備視覺化且美觀的九九乘法圖表卡片排列。
3. **學生成績登入系統**: 具備基礎新增、讀取、刪除管理功能的迷你成績應用程式，並能自動判斷成績是否及格。
4. **AI 財經新聞 Agent**: 模擬 AI 助理自動生成最新財經新聞，具備一鍵生成與動態漸進顯示效果。
