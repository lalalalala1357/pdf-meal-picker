# pdf-meal-picker
上傳PDF菜單，自動分類並隨機抽一組「主食 + 副食」，支援飲料 / 點心分類與預算、熱量限制
# 📄 PDF Meal Picker - 餐點抽籤工具

這是一個簡單實用的網頁工具，只要上傳包含「分類、名稱、大卡、價格」的 PDF 餐點列表，系統就會自動分類並支援：

✅ 隨機抽出一組主食 + 副食（飲料或點心）  
✅ 可選擇副食類型（飲料 / 點心 / 全部）  
✅ 設定預算上限（元）  
✅ 設定熱量上限（kcal）

---

## 🚀 線上體驗網址（GitHub Pages）

👉 [點我開始抽](https://lalalalala1357.github.io/pdf-meal-picker/)

---

## 🧾 PDF 格式範例

請使用表格型 PDF，每行包含以下欄位：

| 分類 | 名稱     | 大卡 | 價格 |
|------|----------|------|------|
| 主餐 | 雞腿便當 | 750  | 90   |
| 飲料 | 紅茶     | 90   | 25   |
| 點心 | 蛋餅     | 400  | 35   |

---

## 🛠 使用方法

1. 打開網站 → 上傳 PDF 檔案
2. 網頁會自動分類並顯示所有項目
3. 選擇：
   - 副食分類（全部 / 飲料 / 點心）
   - 預算上限（例如：120 元）
   - 熱量上限（例如：1000 kcal）
4. 點擊「🎯 抽一組」即可獲得推薦搭配！

---

## 💡 技術細節

- 前端使用：Vanilla JS（純 JavaScript）
- PDF 解析套件：[Mozilla PDF.js](https://mozilla.github.io/pdf.js/)
- 不需後端或伺服器，可直接部署於 GitHub Pages

---

## 🖥 部署方式（GitHub Pages）

1. 建立一個公開 GitHub repository
2. 上傳 `index.html`
3. 設定 GitHub Pages：
   - Branch：`main`
   - Folder：`/root`
4. 系統將會提供你的網頁網址，例如：
