# 礦工 SQL 學院

用 Minecraft 的生物、物品與玩家資料學 SQL 的闖關網站。全站繁體中文，SQL 直接在瀏覽器裡執行，不需要安裝任何東西。

線上版：https://jun32036.github.io/minecraft-sql-playground/

## 內容

- 30 關，分成六章：基礎查詢、條件篩選、整理結果、統計分組、多表查詢、視窗函數
- 每關有教學、範例、任務、提示與參考答案，執行後和預期結果並排比對
- 7 張資料表：`mobs`、`items`、`players`、`biomes`、`inventory`、`mob_drops`、`mining_log`
- 自由練習模式，不判對錯

## 在本機執行

整個網站只有一個 `index.html`，用瀏覽器打開就能用。SQL 引擎是從 cdnjs 載入的 [sql.js](https://github.com/sql-js/sql.js)，所以需要網路。

## 說明

非官方學習網站，與 Mojang、Microsoft 無關。闖關設計參考「SQL 之母」。玩家與挖礦紀錄是虛構的練習資料。
