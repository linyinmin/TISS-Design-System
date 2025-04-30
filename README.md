# TISS Design System

TISS國家科學運動中心的設計系統，提供一致的視覺風格和元件庫。

## 安裝

1. 將 `scss` 資料夾複製到您的專案中
2. 在您的專案中引入主要的SCSS檔案：

```scss
@import 'path/to/scss/tiss.scss';
```

## 顏色系統

### 主要顏色
- 朝活藍 (#77CBF2)
- 植蘊綠 (#00A886)
- 躍動藍 (#004D9F)

### 輔助顏色
- 星曜黃 (#FACB00)
- 日橙橘 (#F29027)
- 沁湖藍 (#00B1AD)

## 元件

### 按鈕
```html
<!-- 主要按鈕 -->
<button class="tiss-btn tiss-btn-primary">主要按鈕</button>

<!-- 次要按鈕 -->
<button class="tiss-btn tiss-btn-secondary">次要按鈕</button>

<!-- 強調按鈕 -->
<button class="tiss-btn tiss-btn-accent">強調按鈕</button>

<!-- 外框按鈕 -->
<button class="tiss-btn tiss-btn-outline tiss-btn-primary">外框按鈕</button>

<!-- 按鈕尺寸 -->
<button class="tiss-btn tiss-btn-primary tiss-btn-sm">小型按鈕</button>
<button class="tiss-btn tiss-btn-primary tiss-btn-lg">大型按鈕</button>
```

### 表單元件
```html
<!-- 文字輸入框 -->
<div class="tiss-form-group">
    <label class="tiss-label">標籤</label>
    <input type="text" class="tiss-input" placeholder="請輸入文字">
</div>

<!-- 下拉選單 -->
<select class="tiss-select">
    <option>選項 1</option>
    <option>選項 2</option>
</select>

<!-- 多行文字框 -->
<textarea class="tiss-textarea" placeholder="請輸入多行文字"></textarea>

<!-- 核取方塊 -->
<input type="checkbox" id="checkbox1" class="tiss-checkbox">
<label for="checkbox1">核取方塊</label>

<!-- 單選按鈕 -->
<input type="radio" id="radio1" class="tiss-radio" name="radio">
<label for="radio1">單選按鈕</label>
```

### 彈跳視窗
```html
<div class="tiss-modal-backdrop">
    <div class="tiss-modal">
        <div class="tiss-modal-header">
            <h3 class="tiss-modal-title">標題</h3>
            <button class="tiss-modal-close">&times;</button>
        </div>
        <div class="tiss-modal-body">
            <p>內容</p>
        </div>
        <div class="tiss-modal-footer">
            <button class="tiss-btn tiss-btn-outline tiss-btn-primary">取消</button>
            <button class="tiss-btn tiss-btn-primary">確認</button>
        </div>
    </div>
</div>
```

## 工具類別

### 文字顏色
```html
<div class="tiss-text-primary">主要文字顏色</div>
<div class="tiss-text-secondary">次要文字顏色</div>
<div class="tiss-text-accent">強調文字顏色</div>
```

### 背景顏色
```html
<div class="tiss-bg-primary">主要背景顏色</div>
<div class="tiss-bg-secondary">次要背景顏色</div>
<div class="tiss-bg-accent">強調背景顏色</div>
```

### 間距
```html
<div class="tiss-mt-1">上邊距 1</div>
<div class="tiss-mb-2">下邊距 2</div>
<div class="tiss-p-3">內邊距 3</div>
```

### 圓角
```html
<div class="tiss-rounded-sm">小圓角</div>
<div class="tiss-rounded-md">中圓角</div>
<div class="tiss-rounded-lg">大圓角</div>
```

### 陰影
```html
<div class="tiss-shadow-sm">小陰影</div>
<div class="tiss-shadow-md">中陰影</div>
<div class="tiss-shadow-lg">大陰影</div>
```

## 瀏覽器支援

- Chrome (最新版)
- Firefox (最新版)
- Safari (最新版)
- Edge (最新版)

## 授權

本設計系統為TISS國家科學運動中心所有，未經授權不得使用。 