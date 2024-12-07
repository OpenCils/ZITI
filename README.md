# 中文字体托管服务

这是一个基于 Vercel 的中文字体托管服务，目前提供以下字体：

- 仓耳华新体

## 使用方法

在你的 CSS 中添加以下代码：

```css
@font-face {
    font-family: 'CangErHuaXin';
    src: url('https://你的vercel域名/fonts/仓耳华新体.ttf') format('truetype');
    font-weight: normal;
    font-style: normal;
    font-display: swap;
}
```

然后在你的 CSS 中使用：

```css
.your-element {
    font-family: 'CangErHuaXin', sans-serif;
}
```

## 注意事项

1. 请确保你有使用这些字体的相关权限
2. 建议使用 `font-display: swap` 来优化字体加载体验
3. 字体文件较大，请注意网页加载性能
