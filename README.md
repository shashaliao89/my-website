# 個人履歷網頁

一個現代化、響應式的個人履歷網頁，專為面試展示而設計。

## 特色功能

### 🎨 視覺設計
- 現代化的漸層背景和配色方案
- 流暢的動畫效果和過渡
- 響應式設計，支援各種設備
- 專業的排版和視覺層次

### 📱 響應式布局
- 桌面版：完整的多欄布局
- 平板版：自適應的網格系統
- 手機版：單欄垂直布局
- 觸控友好的互動元素

### ⚡ 互動功能
- 平滑滾動導航
- 動態技能進度條
- 數字統計動畫
- 時間軸展示工作經驗
- 表單驗證和提交處理

### 🎯 內容區域
- **首頁**：個人介紹和核心價值
- **關於我**：背景、教育、認證
- **工作經驗**：時間軸式經驗展示
- **技能專長**：技術技能和軟技能
- **聯絡方式**：多種聯絡管道

## 使用說明

### 1. 自訂內容
編輯 `index.html` 文件中的以下內容：

```html
<!-- 替換這些佔位符為您的實際資訊 -->
[您的姓名] → 您的真實姓名
[您的職位/專業領域] → 您的職位
[相關經驗] → 您的專業領域
[核心技能] → 您的核心技能
[工作理念/目標] → 您的工作理念
```

### 2. 工作經驗
在時間軸區域添加您的工作經驗：

```html
<div class="timeline-item">
    <div class="timeline-marker"></div>
    <div class="timeline-content">
        <div class="timeline-header">
            <h3>軟體工程師</h3>
            <span class="timeline-date">2020 - 2023</span>
        </div>
        <h4 class="timeline-company">科技公司</h4>
        <p class="timeline-description">
            負責前端開發和用戶體驗優化
        </p>
        <ul class="timeline-achievements">
            <li>提升了30%的用戶滿意度</li>
            <li>完成了10個重要專案</li>
            <li>帶領5人開發團隊</li>
        </ul>
    </div>
</div>
```

### 3. 技能設定
調整技能進度條的百分比：

```html
<div class="skill-progress" data-width="90%"></div>
```

### 4. 聯絡資訊
更新聯絡方式：

```html
<p>[您的電子郵件]</p>
<p>[您的電話號碼]</p>
<p>[您的LinkedIn連結]</p>
<p>[您的工作地點]</p>
```

### 5. 統計數據
修改個人統計：

```html
<div class="stat-number">5+</div>
<div class="stat-label">工作經驗</div>
```

## 技術規格

- **HTML5**：語義化標記
- **CSS3**：現代化樣式和動畫
- **JavaScript**：互動功能和動畫
- **響應式設計**：支援所有設備
- **無依賴**：純原生技術實現

## 瀏覽器支援

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 部署方式

### 本地預覽
1. 下載所有文件到同一個資料夾
2. 用瀏覽器開啟 `index.html`
3. 開始自訂您的內容

### 線上部署
1. 上傳文件到任何網頁主機
2. 或使用 GitHub Pages、Netlify、Vercel 等免費服務
3. 分享您的網址給面試官

## 自訂建議

### 顏色主題
在 `styles.css` 中修改主要顏色：

```css
/* 主要藍色 */
#2563eb → 您喜歡的顏色

/* 漸層背景 */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### 字體
替換 Google Fonts 連結：

```html
<link href="https://fonts.googleapis.com/css2?family=您的字體:wght@300;400;500;700&display=swap" rel="stylesheet">
```

### 動畫速度
調整動畫持續時間：

```css
transition: all 0.3s ease; /* 修改 0.3s */
```

## 注意事項

1. **圖片**：如需添加個人照片，建議使用 300x300px 的方形圖片
2. **內容長度**：保持內容簡潔，避免過多文字
3. **載入速度**：所有資源都已優化，載入速度快
4. **SEO**：可添加 meta 標籤提升搜尋引擎優化

## 支援

如有任何問題或需要客製化服務，歡迎聯絡。

---

**祝您面試順利！** 🎉
