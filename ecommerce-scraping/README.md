# Bright Data 亚马逊商品抓取器

本项目演示如何使用 Bright Data 的 Scraping Browser 在 Amazon.com 上搜索商品。它提供了一个通过自动化浏览器控制进行网页抓取的实用示例。

<a href="https://codesandbox.io/p/devbox/github/luminati-io/bright-data-scraping-browser-nodejs-project?file=%2Famazon-product-scraping.js" target="_blank" rel="noopener">在 CodeSandbox 中打开</a>，使用 GitHub 账号登录，然后 fork 该仓库以开始修改。

### 开始使用

1. 在 `amazon-product-scraping.js` 中将 `YOUR_BRIGHT_DATA_SCRAPING_BROWSER_ENDPOINT` 替换为你实际的 Bright Data Scraping Browser WebSocket 端点
2. 运行 `node amazon-product-scraping.js` 开始抓取

## 💻 使用方法

1. 在 `amazon-product-scraping.js` 中将 `YOUR_BRIGHT_DATA_SCRAPING_BROWSER_ENDPOINT` 替换为你实际的 Bright Data Scraping Browser WebSocket 端点

2. 在 `amazon-product-scraping.js` 中修改搜索参数：
   ```javascript
   const SEARCH_TERM = "laptop";   // 修改为你的搜索关键词
   ```

3. 运行脚本：
   ```bash
   node amazon-product-scraping.js
   ```

## 📊 示例输出

```
📊 亚马逊搜索结果（关键词："laptop"）
=======================

#1 ASUS Vivobook Go 15 L510 Thin & Light Laptop, 15.6" FHD Display, Intel Celeron N4020 Processor, 4GB RAM, 64GB Storage, Windows 11 Home in S Mode, 1 Year Microsoft 365, Star Black, L510MA-WB04
   💰 价格: $249.99
   ⭐ 评分: 4.3 / 5 星
   --------------------------------------------------

#2 Acer Aspire 3 A315-24P-R7VH Slim Laptop | 15.6" Full HD IPS Display | AMD Ryzen 3 7320U Quad-Core Processor | AMD Radeon Graphics | 8GB LPDDR5 | 128GB NVMe SSD | Wi-Fi 6 | Windows 11 Home in S Mode
   💰 价格: $299.99
   ⭐ 评分: 4.4 / 5 星
   --------------------------------------------------

#3 HP 15.6" HD Laptop, Intel Celeron N4500, 8GB RAM, 256GB SSD, Silver, Windows 11 Home in S Mode
   💰 价格: $279.00
   ⭐ 评分: 4.2 / 5 星
   --------------------------------------------------

#4 Lenovo IdeaPad 1 14 Laptop, 14.0" HD Display, Intel Celeron N4020, 4GB RAM, 64GB Storage, Intel UHD Graphics 600, Win 11 in S Mode, Cloud Grey
   💰 价格: $199.99
   ⭐ 评分: 4.1 / 5 星
   --------------------------------------------------

#5 HP 14" HD Laptop, Intel Celeron N4020, 4GB RAM, 64GB Storage, Pale Rose Gold, Windows 11 Home in S Mode
   💰 价格: $219.99
   ⭐ 评分: 4.3 / 5 星
   --------------------------------------------------

✅ 共找到 5 个与 "laptop" 相关的商品
```
