# 我的GitHub Pages博客

这是一个使用GitHub Pages托管的简单个人博客。

## 功能特点

- 响应式设计，支持各种设备
- 深色/浅色主题切换
- 平滑滚动和动画效果
- 现代化的UI设计

## 如何使用

1. 克隆或下载这个仓库
2. 在GitHub上创建一个新的仓库，命名为 `yourusername.github.io`
3. 将代码推送到新创建的仓库
4. 访问 `https://yourusername.github.io` 查看你的博客

## 自定义内容

### 修改个人信息

在 `index.html` 文件中修改以下部分：

```html
<!-- 修改标题和描述 -->
<h1 class="logo">我的博客</h1>
<h2>欢迎来到我的博客</h2>
<p>分享技术、生活和思考的地方</p>

<!-- 修改关于我部分 -->
<p>这是一个简单的个人博客...</p>

<!-- 修改联系信息 -->
<div class="contact-item">
    <i class="fas fa-envelope"></i>
    <span>your-email@example.com</span>
</div>
```

### 添加新文章

在 `index.html` 的博客部分添加新的文章卡片：

```html
<article class="blog-card">
    <div class="blog-image">
        <img src="图片URL" alt="文章缩略图">
    </div>
    <div class="blog-content">
        <h3>文章标题</h3>
        <p>文章简介...</p>
        <div class="blog-meta">
            <span class="date">发布日期</span>
            <span class="tags">标签1, 标签2</span>
        </div>
    </div>
</article>
```

### 自定义样式

在 `style.css` 文件中修改CSS变量来自定义颜色主题：

```css
:root {
    --primary-color: #4a6fa5;  /* 主色调 */
    --accent-color: #ff6b6b;   /* 强调色 */
    /* 其他颜色变量... */
}
```

## 部署到GitHub Pages

1. 确保你的仓库名称格式为 `yourusername.github.io`
2. 在仓库设置中启用GitHub Pages
3. 选择源分支（通常是main或master）
4. 保存设置后，GitHub会自动构建和部署你的网站

## 技术栈

- HTML5
- CSS3 (Grid, Flexbox, CSS Variables)
- JavaScript (ES6+)
- Font Awesome (图标)
- Google Fonts (字体)

## 许可证

MIT License