# 麵包屑

- CSS中的加號(+) 同一階層後的標籤(siblings)會受影響
```html
<li></li>
<li></li>
<li></li>
```
```css
.li + li {
    padding:10px;
}
```

li後同層級的li才會受影響，依上面的例子指的是第一個li以外的li。(有點遞迴概念？)

![image](https://github.com/willynpi/css-coke/blob/main/N009/screenshot.png)