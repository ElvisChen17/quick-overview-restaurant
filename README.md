# 飽點｜附近餐廳快速推薦工具 🍜

一鍵查找周邊高評價餐廳，讓你不用再一間一間打開 Google Map！

## 🌟 特色功能
- ✅ 支援輸入地址後快速定位
- ✅ 自動抓取附近熱門餐廳／咖啡廳／火鍋／燒肉／飲料店
- ✅ 顯示營業時間、近期評論、Google 評分
- ✅ 自訂搜尋距離（500 公尺～2 公里）
- ✅ 地圖互動與點卡片同步（放大地圖、開啟 info window）

## 🧪 使用方式
1. Clone 本專案：
   ```bash
   git clone https://github.com/你的帳號/restaurant-finder.git
   ```
2. 開啟 `index.html` 檔案，或使用 GitHub Pages 發佈靜態頁面。

## 🔐 注意事項
- 本專案使用 Google Maps API，**請勿上傳公開 API 金鑰！**
- 請至 [Google Cloud Console](https://console.cloud.google.com/) 建立自己的金鑰，並套用於以下兩處：
   - 地圖初始化 `<script src="...key=你的金鑰">`
   - `searchLocation()` 函數中的 `apiKey` 變數

## 👀 預覽畫面

![screenshot](https://raw.githubusercontent.com/elvis860812/image-assets/main/preview.jpg)

## 🤖 技術使用
- HTML / CSS / JavaScript
- Google Maps JavaScript API
- Places Nearby Search API
- Places Details API
- Proxy API (AllOrigins) 解決 CORS 問題

## 📫 聯絡我
Elvis Chen ｜elvischen17 [at] gmail [dot] com  
作品展示連結：https://elvischen17.github.io/supply-chain-dashboard-demo/
