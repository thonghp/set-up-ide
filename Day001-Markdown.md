# Day 1: MARKDOWN USER MANUAL

## Mục Lục Nội Dung

- [1. Tạo Heading](#1-tạo-heading)
- [2. Tạo List](#2-tạo-list)
  - [2.1. UnOderlist](#21-unoderlist)
  - [2.2. Orderlist](#22-orderlist)
- [3. Tạo đoạn trích dẫn](#3-tạo-đoạn-trích-dẫn)
- [4. Tạo in đậm và in nghiêng](#4-tạo-in-đậm-và-in-nghiêng)
- [5. Tạo hình ảnh](#5-tạo-hình-ảnh)
- [6. Biểu thị từ hoặc cụm từ dưới dạng code](#6-biểu-thị-từ-hoặc-cụm-từ-dưới-dạng-code)
- [7. Rule](#7-rule)
- [8. Tạo Table](#8-tạo-table)
- [9. Tạo Link](#9-tạo-link)
- [10. Thao tác markdown chuyển qua pdf](#10-thao-tác-markdown-chuyển-qua-pdf)

## 1. Tạo Heading

Tạo heading bằng cách thêm syntax `#` ở phía trước, 1 dấu đại diện cho heading 1, 2 dấu đại diện cho heading 2, tối đa là tới heading 6

> syntax: # heading

## 2. Tạo List

##### 2.1. UnOderlist

Tạo unOrderlist bằng cách thêm syntax `-` ở phía trước, tạo phân cấp thì thêm 1 khoảng cách ở phía trước, tương tự cho orderlist chỉ khác ở chổ `-` thì orderlist dùng số đếm

- muc 1
- muc 2
  - muc 2.1
  - muc 2.2

##### 2.2. Orderlist

1. muc 1
2. muc 2
   1. muc 2.1
   2. muc 2.2

> syntax: - item với unorderlist (1. item với orderlist)

## 3. Tạo đoạn trích dẫn

Tạo khối trích dẫn bằng cách thêm `>` ở phía trước

> syntax: >

## 4. Tạo in đậm và in nghiêng

Tạo chữ **đậm** và chữ in *nghiêng*

> syntax: ** bold ** and * italic *

## 5. Tạo hình ảnh

![alt text](/assets/writer.png)

> syntax: ! [ hiển thị khi ảnh bị lỗi ] (/assets/writer.png)

## 6. Biểu thị từ hoặc cụm từ dưới dạng code

Example: `.css`

> syntax: nằm ở trong dấu ``

## 7. Rule

```html
<p> chú thích html <p>
```

```javascript
let num = Math.random();
```

## 8. Tạo Table

Mặc định căn giữa các cột

| Day   | Topic | Link |
| ----- | :---- | ---: |
| Day 1 | a     |    b |

## 9. Tạo Link

[link tham khảo cheetsheet markdown][b]

## 10. Thao tác markdown chuyển qua pdf

- Yêu cầu tải extension markdown pdf
- Muốn export ra pdf nhấp chuột phải vào bất kỳ vị trí trong trang markdown
- Tạo ngắt dòng trong markdown khi xuất ra pdf
  1. Vào file => preferences => user snippets => gõ markdown.json 
  ![alt text](/assets/day-01-setting-pagebreak.png)
  2. Thêm snippet 
  ![alt text](/assets/day-01-add-snippet-pagebreak.jpg)
  3. Giờ chỉ cần gõ pagebreak se thêm ngắt đoạn trong pdf
- Tạo gợi ý code trong markdown
  1. Vào file => preferences => setting 
  ![alt text](/assets/day-01-add-snippet-setting.jpg)
  2. Thêm snippet suggestion 
  ![alt text](/assets/day-01-add-snippet-suggestion.jpg)

[b]: https://www.markdownguide.org/cheat-sheet/
