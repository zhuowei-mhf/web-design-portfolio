# Web Design TA Showcase

## 1. 專案概述 (Project Overview)

本專案為應徵陽明交通大學「基礎網頁設計」課程教學助理（TA）所建置之技術展示系統。專案淬鍊自 2025-2026 於清華大學實際參與研發之「教育部 USR 計畫網路平台」前端核心成果。

本站將真實專案的截圖與可互動的網頁元件並列呈現：

- **USR 網站實作（左側）：** 展示過去在 USR 專案中負責的真實 UI 介面與系統架構。
- **本網站測試（右側）：** 針對課程目標，使用純粹的 HTML5、CSS3 與 JavaScript 重新建構的可互動範例。

## 2. 核心技術與展示模組 (Core Modules)

- **響應式佈局與互動 (RWD Layout)**

  - **技術亮點：** 結合 CSS Flexbox 與 Bootstrap 5，實現在不同裝置的顯示方式。
  - **列印功能改善：** 實作 `@media print` 規則，確保匯出 PDF 或列印時自動隱藏導覽列與按鈕等非核心元素，呈現乾淨的文件版面。

- **資料表格設計 (Data Table)**

  - **技術：** 基於 HTML 的`<form>`並運用 `table-responsive` 容器與 `white-space: nowrap` 建立橫向安全滾動機制，並落實 `<thead>` 與 `<tbody>` 等結構。

- **動態表單與輸入驗證 (Form Validation)**

  - **技術：** 統整單選（Radio）、下拉選單（Select）、文字輸入（Textarea）與核取方塊（Checkbox），並實作防呆驗證確保使用者的填答情況。

- **彈窗功能**

## 3. 專案架構 (Directory Structure)

```text
web-design-portfolio/
├── index.html          # 系統主入口
├── css/
│   └── style.css       # 包含客CSS 變數與元件細節修飾
├── assets/
│   └── img/            # 影像資源目錄
│       ├── usr_home.png  # USR 專案首頁截圖
│       ├── usr_table.png # USR 後台表格截圖
│       └── usr_form.png  # USR 問卷表單截圖
└── README.md           # 本網頁技術說明文件
```
