# ![](https://drive.google.com/uc?id=10INx5_pkhMcYRdx_OO4rXNXxcsvPtBYq) Markdown 基本語法

---

<!--ts-->
## 目錄
* [簡介](#簡介)
* [標題](#標題)
* [錨點](#錨點)
* [強調和粗體](#強調和粗體)
* [引用](#引用)
* [鏈接和圖片](#鏈接和圖片)
* [代碼區塊](#代碼區塊)
* [參考資料](#參考資料)
<!--te-->

---

## 簡介.
Markdown 是一種輕量級的標記語言，設計用於簡單地編寫格式化的純文本內容。<br>
- 它具有簡單、易讀易寫的語法，並且可以輕鬆轉換為HTML等其他格式。<br>
- 它的優點在於簡單易學，且能夠輕鬆轉換為其他格式，非常適合用於編寫文檔、筆記、部落格文章等。<br>

下面會列出一些常見的 Markdown 語法示例.<br>

---

## 標題
使用 # 符號表示標題，數量表示級別（# 為一級標題，## 為二級標題，以此類推）。
``` markdown
# 一級標題
## 二級標題
### 三級標題
```

---

## 錨點
使用  `[顯示文字](#連結標題名稱)` 來建立錨點。
``` markdown
## title
- [display title name](#title)
```
```diff
- 注意，標題的連結名稱不能有其他特殊字元，可以用空格，但連結的方式要改成用'-'符號來做連結，如下所示：
```
``` markdown
## i am title
- [display title name](#i-am-title)
```

---

## 列表
使用 * 或 - 來建立無序列表，使用數字加點號來建立有序列表。
``` markdown
- 項目一
- 項目二
- 項目三

1. 項目一
2. 項目二
3. 項目三
```

---

## 強調和粗體
使用 * 或 _ 包圍文字來表示斜體，使用兩個 * 或 _ 包圍文字來表示粗體。
``` markdown
*斜體文字*
_斜體文字_

**粗體文字**
__粗體文字__
``` 

---

## 引用

使用 > 符號表示引用。
``` markdown
> 這是引用的內容。
```

---

## 鏈接和圖片
使用 `[顯示文字](連結URL)` 來建立超鏈接，使用`![替代文字](圖片URL)` 來插入圖片。
``` markdown
[OpenAI](https://openai.com)
![Logo](https://example.com/logo.png)
```

如果想要讓圖片縮小的話，可以用html的語法來達成效果.
``` markdown
<img src="https://example.com/logo.png" height="70%" width="70%"/>
```

---

## 代碼區塊
使用三個反引號 ` 來標示代碼塊，並指定代碼塊的語言。
``` markdown
```javascript
function sayHello() {
    console.log("Hello!");
}
```

---


## 參考資料
* [Markdown - 語法說明](https://markdown.tw/) <br>

---

<!--ts-->
#### [目錄 ↩](#目錄)
<!--te-->
