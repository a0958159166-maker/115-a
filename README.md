# Markdown 語法教學

## 標題 (Headers)

# This is an H1
## This is an H2
### This is an H3
#### This is an H4
##### This is an H5
###### This is an H6

也可以使用底線語法：

This is an H1
=============

This is an H2
-------------

---

## 字型樣式 (Typography)

**粗體**
*斜體*
~~刪除線~~

---

## 列表 (Lists)

### 無序列表
* Red
* Green
* Blue

或使用 `+` 或 `-`：
+ Red
+ Green
+ Blue

- Red
- Green
- Blue

### 有序列表
1. Bird
2. McHale
3. Parish

---

## 連結 (Links)

### 連外部超連結
[Yahoo 奇摩](http://tw.yahoo.com)

或直接加上角括號：
<http://tw.yahoo.com>

### 連內部超連結
[GIT分支](/chapter_3_branch/git.html)

---

## 引言區塊 (Blockquotes)

### 多行引言區塊
> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.

### 階層式引言區塊
> 新北市
>> 板橋區
>> 中和區
> 桃園縣
>> 大溪鎮
>> 龜山鄉

---

## 程式碼區塊 (Code Blocks)

### 行內小區塊
使用 1 個反引號：`小區塊`

### 程式語言高亮顯示 (程式碼大區塊)
使用 3 個反引號，並指定語言名稱：

```js
$scope.cookieGet = function(key){
    $scope.cookieResult =$cookieStore.get(key);
    console.log ($scope.cookieResult);
}
