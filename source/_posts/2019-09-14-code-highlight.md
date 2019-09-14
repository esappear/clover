---
title: 代码高亮和表格效果测试
date: 2019-09-14 15:49:22
tags: test
photos: images/highlight.png
---
# Code Highlight
## js
```js
// 大数相加
function add(n1, n2) {
  const a1 = n1.split('').reverse();
  const a2 = n2.split('').reverse();
  const result = [];
  for (let i = 0, l = Math.max(a1.length, a2.length); i < l; i++) {
    result[i] = (result[i] || 0) + parseInt(a1[i] || 0) + parseInt(a2[i] || 0);
    while (result[i] >= 10) {
      result[i] -= 10;
      result[i + 1] = (result[i + 1] || 0) + 1;
    }
  }
  return result.reverse().join('');
}
```
## html
```html
<meta name="viewport" content="width=device-width, initial-scale=1">
<script type='application/javascript' src='/path/to/fastclick.js'></script>
```
## css
```css
div {
  color: red;
  background-color: gray;
}
```
## bash
```bash
git clone https://github.com/esappear/hexo-theme-clover themes/clover
```

# Table
| TEST | TEST |
| - | - |
| what | what |
| what | what |
| what | what |
| what | what |


