# 六角學院 2023 軟體工程師體驗營－切版作業一
作業連結：[切版任務作業一－AI 工具王－產品優勢卡片設計](https://rpg.hexschool.com/task/342/show)

## Table of contents
- [Overview](#overview)
  - [Link](#link)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)

## Overview
- 第一次總共花費約 2 小時，0.5 小時完成大架構，1.5 小時進行 HTML、CSS 調整
- 第二次總共花費約 1 小時，針對助教回饋修改，及查詢 flex-grow 語法
- 第三次總共花費約 0.5 小時，針對助教回饋修改
- 第四次總共花費約 0.2 小時，針對助教回饋修改

### Link
- Live Site URL: [AI 工具王](https://chunjull.github.io/hexschool-experience-camp-task-1/)

## My process

### Built with
- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned
第一次：
- 使用 Emmet 加速網頁開發
- 語意化命名標籤

第二次：
- 在卡片的 hashtag 加上 a 或 button 標籤，或添加 cursor: pointer; 提示使用者可點選，有助於提升使用者體驗
- img 的 width 設為 100%，使圖片符合父層的寬度
- img 加上 hover 效果
- 勿寫死卡片高度，建議使用 flex-grow:1 分配 Flex 內多餘的空間

第三次：
- 移除 .card-info 子層 hashtag a 標籤外層的 p 標籤

第四次：
- 使用 overflow 將 image 超出邊框的部分隱藏
