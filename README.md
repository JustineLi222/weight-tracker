# ⚖️ 體重追蹤 (Weight Tracker)

單檔 HTML 體重記錄工具 — 唔使安裝、唔使伺服器，打開即用。

🔗 **Live site:** https://justineli222.github.io/weight-tracker/

## 功能

- 📝 每日體重記錄
- ⚖️ 雙單位切換（**kg / lb**）
- 🎯 目標體重設定 + 進度顯示
- 📈 圖表 + 統計（canvas 繪製，唔使外部 library）
- 🔮 預測（以目前趨勢估計達成目標日期）
- 📋 Export / Import / Clipboard — 備份同搬移資料
- 🍎 一鍵複製到 Apple Notes 記錄

## 私隱

- 所有資料只存喺**你嘅瀏覽器**（`localStorage`），**唔會上傳任何伺服器**
- 冇追蹤、冇 analytics、冇 cookie

## 使用

直接開 `index.html` 就得。想離線用都可以下載落嚟開。

## 開發

- 源碼就係單一個 `index.html`（冇 build step、冇 dependency）
- 改完直接 push，GitHub Pages 會自動更新
