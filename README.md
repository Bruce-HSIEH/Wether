# 天氣小人

一個會跟著天氣換裝、做出反應的小男孩動畫網頁。打開就會抓你所在位置的即時天氣，晴天戴帽子、下雨撐傘、颳風傘被吹走。

**網址**：https://bruce-hsieh.github.io/Wether/

## 功能

- 依目前位置自動取得天氣
- 小人的裝備和表情會隨天氣變化（晴、陰、雨、雪、雷雨、霧、強風）
- 顯示溫度、體感溫度、降雨量和逐時預報
- 可以加到 iPhone 主畫面，當成 App 使用

## 資料來源

- 天氣：[Open-Meteo](https://open-meteo.com/)（免費天氣 API，不需申請金鑰）
- 地名：[BigDataCloud](https://www.bigdatacloud.com/)（把經緯度轉成城市名稱）

## 檔案

| 檔案 | 用途 |
| --- | --- |
| `index.html` | 網頁本體，畫面、樣式和程式都在這一個檔案裡 |
| `README.md` | 這份說明 |

## 如何更新

修改 `index.html` 後 commit 並 push 到 `main` 分支，GitHub Pages 會在一兩分鐘內自動更新網址上的內容。
