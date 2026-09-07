# 生物遊戲專案

這是一個基於 Scratch/TurboWarp 打包的瀏覽器遊戲專案，主要內容是以「生物」為主題的互動式遊戲，並以 HTML + JavaScript 方式執行。

## 專案概述

本專案的核心檔案如下：

- `index.html`：遊戲入口頁面
- `script.js`：遊戲執行與啟動程式碼
- `assets/project.json`：專案實際內容資料，包含舞台、角色、變數與腳本邏輯

這個專案是由 TurboWarp 包裝版本，使用者可直接在瀏覽器中開啟並執行，已經包裝成網頁。

## 遊戲內容

從專案資料中可觀察到以下角色與元素：

本遊戲屬於生物模擬器，總共有三級生物層。

## 專案結構

```text
biology/
├── index.html
├── script.js
├── README.md
└── assets/
    └── project.json
```

## 啟動方式

### 直接開啟網頁
1. 進入 ``` https://fuguangji.github.io/biology ```

## 使用說明

- 打開Github Pages網頁
- 如需調整遊戲內容，請修改 `assets/project.json` 或相關 Scratch 專案來源

## 開發與維護

這個專案的本質是 Turbowarp 專案（與Sratch不相容）轉成 HTML 包裝版本，較適合使用以下方式維護：

- 直接修改 Scratch 原始專案後重新匯出
- 調整 `assets/project.json` 內的設定與腳本
- 修改 `script.js` 以改善載入或互動行為

## 注意事項

- 此專案是前端瀏覽器型遊戲，不需要額外安裝依賴
- 因為是打包的 TurboWarp 專案，部分檔案是產物，不適合直接手動編輯
- 若要進一步修改遊戲內容，需回到 TurboWarp 專案原始來源，有任何問題請使用Issue提出，我將視情況調整。

