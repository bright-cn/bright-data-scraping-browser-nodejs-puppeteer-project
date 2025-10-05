# Bright Data 酒店搜索抓取器

本项目演示如何使用 Bright Data 的 Scraping Browser 在 Booking.com 上搜索酒店。它提供了一个通过自动化浏览器控制进行网页抓取的实用示例。

<a href="https://codesandbox.io/p/devbox/github/luminati-io/bright-data-scraping-browser-nodejs-project?file=%2Fbooking-hotel-scraping.js" target="_blank" rel="noopener">在 CodeSandbox 中打开</a>，使用 GitHub 账号登录，然后 fork 该仓库以开始修改。

### 开始使用

1. 在 `booking-hotel-scraping.js` 中将 `YOUR_BRIGHT_DATA_SCRAPING_BROWSER_ENDPOINT` 替换为你实际的 Bright Data Scraping Browser WebSocket 端点
2. 运行 `node booking-hotel-scraping.js` 开始抓取

## 💻 使用方法

1. 在 `booking-hotel-scraping.js` 中修改搜索参数：
   ```javascript
   const SEARCH_LOCATION = "New York";  // 修改为你想要的地点
   const CHECK_IN_DAYS_FROM_NOW = 1;    // 调整入住日期
   const CHECK_OUT_DAYS_FROM_NOW = 2;   // 调整退房日期
   ```

2. 运行脚本：
   ```bash
   node booking-hotel-scraping.js
   ```

## 📊 示例输出

```
📊 搜索结果:
==================
┌─────────┬─────┬────────────────────┬──────────┬─────────┐
│ (index) │  #  │     Hotel Name     │  Price   │ Rating  │
├─────────┼─────┼────────────────────┼──────────┼─────────┤
│    0    │  1  │ Hotel Name 1       │ $100     │ 8.5     │
│    1    │  2  │ Hotel Name 2       │ $150     │ 9.0     │
│    2    │  3  │ Hotel Name 3       │ $200     │ 8.8     │
└─────────┴─────┴────────────────────┴──────────┴─────────┘
```
