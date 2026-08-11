---
title: Markdown 完整格式示例
date: 2026-08-12 10:00:00
tags:
  - Markdown
  - 示例
  - 教程
categories:
  - 技术
  - 博客
description: 这是一篇包含所有Markdown格式的示例文章
cover: /images/cover.jpg
---

## 欢迎

这是一篇展示所有**Markdown**格式的示例文章，适用于Hexo博客。你可以参考这篇文档来了解各种格式的写法。

<!-- more -->

---

## 1. 标题

# H1 标题
## H2 标题
### H3 标题
#### H4 标题
##### H5 标题
###### H6 标题

---

## 2. 文本样式

- **粗体文本**：使用 `**粗体**`
- *斜体文本*：使用 `*斜体*`
- ***粗斜体***：使用 `***粗斜体***`
- ~~删除线~~：使用 `~~删除线~~`
- <u>下划线</u>：使用 `<u>下划线</u>`
- `行内代码`：使用 `` `行内代码` ``

---

## 3. 引用

> 这是一级引用
> 
> > 这是二级引用
> > 
> > > 这是三级引用

---

## 4. 列表

### 无序列表

- 项目 1
- 项目 2
  - 子项目 2.1
  - 子项目 2.2
    - 子项目 2.2.1
- 项目 3

### 有序列表

1. 第一项
2. 第二项
   1. 子项 2.1
   2. 子项 2.2
3. 第三项

### 任务列表

- [x] 已完成任务
- [ ] 未完成任务
- [ ] 待办事项

---

## 5. 代码

### 行内代码

使用 `console.log('Hello World')` 输出信息。

### 代码块

```javascript
// JavaScript 示例
function helloWorld() {
  const message = 'Hello, World!';
  console.log(message);
  return message;
}

helloWorld();
```

```python
# Python 示例
def hello_world():
    message = "Hello, World!"
    print(message)
    return message

if __name__ == "__main__":
    hello_world()
```

```bash
# Shell 命令
npm install
hexo generate
hexo server
```

```html
<!-- HTML 示例 -->
<!DOCTYPE html>
<html>
<head>
  <title>Hello World</title>
</head>
<body>
  <h1>Hello, World!</h1>
</body>
</html>
```

```css
/* CSS 示例 */
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 20px;
  background: #f0f0f0;
}
```

---

6. 链接

· 普通链接
· 带标题的链接
· 
· [引用链接][1]

---

7. 图片

https://via.placeholder.com/800x400

带链接的图片

https://via.placeholder.com/800x400

---

8. 表格

基本表格

左对齐 居中对齐 右对齐
单元格 单元格 单元格
内容 1 内容 2 内容 3
长内容 更长内容 最长内容

带格式的表格

功能 语法 示例
粗体 **文本** 粗体
斜体 *文本* 斜体
代码  `代码`  代码

---

9. 分隔线

---

---

---

---

10. 脚注

这里是脚注示例[^1]，这里也是[^2]。

[^1]: 这是脚注 1 的内容。
[^2]: 这是脚注 2 的内容，可以包含格式化文本。

---

11. 数学公式 (如果支持 MathJax)

E = mc^2

行内公式：$a^2 + b^2 = c^2$

\sum_{i=1}^{n} i = \frac{n(n+1)}{2} 

\int_{0}^{\infty} e^{-x} dx = 1 

---

12. 折叠区块 (HTML)

<details>
  <summary>点击展开查看详情</summary>

这是折叠内容，可以包含 Markdown 格式。

· 列表项 1
· 列表项 2

```javascript
  console.log('折叠内的代码');
```

</details>

---

13. 高亮标记 (如果支持)

==高亮文本== 使用 ==高亮==

---

14. 自定义容器 (Hexo 特有)

{% note primary %}
主要提示：这是一条重要信息。
{% endnote %}

{% note success %}
成功提示：操作成功完成。
{% endnote %}

{% note warning %}
警告提示：请注意这个警告。
{% endnote %}

{% note danger %}
危险提示：这是危险操作警告。
{% endnote %}

---

15. 内嵌 HTML

<div style="background: #f5f5f5; padding: 15px; border-radius: 5px;">
  <p style="color: #333;">这是一个包含 <strong>HTML</strong> 的自定义容器。</p>
  <p style="color: #666;">可以使用任何 HTML 标签和样式。</p>
</div>

---

16. 图片相册 (Hexo 插件)

{% gallery %}
https://via.placeholder.com/400x300
https://via.placeholder.com/400x300
https://via.placeholder.com/400x300
{% endgallery %}

---

17. 视频嵌入

<iframe width="560" height="315" src="https://www.youtube.com/embed/dQw4w9WgXcQ" frameborder="0" allowfullscreen></iframe>

---

18. 文本对齐

<p align="center">居中对齐文本</p>
<p align="right">右对齐文本</p>

---

总结

以上就是 Markdown 在 Hexo 中的完整格式示例。你可以在写博客时参考这些格式，创作出更丰富、更美观的内容。

建议：

· 合理使用标题层级
· 适当添加图片和代码块
· 保持文章排版整洁
· 添加阅读更多标记 <!-- more -->

如有疑问，欢迎在评论区留言交流！ 😊