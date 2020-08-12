# HTML 入门笔记 1

## HTML 历史

HTML 是李爵士在 1990 年发明的，他同时发明了 URL，HTTP，HTML，并创立了 W3C。由此开启了人类上网冲浪的大门。

## HTML 起手

```html
<!DOCTYPE html>
<!-- 文件类型html -->
<html lang="zh-CN">
<!-- 默认lang="en" 可以改为"zh-CN" -->
<head>
    <meta charset="UTF-8" />
    <!-- 文件字符编码 -->
    <meta name="viewport" content="width=device-width,initial-scale+1.0" />
    <!-- 视口，禁用缩放，兼容手机 -->
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    <!-- 告诉IE使用最新内核 -->
    <title>这里写标题<title>
</head>
<body>
这里写内容
<body>
</html>
```

## 常用的章节标签

1. 标题 h1~h6
2. 章节 section
3. 文章 article
4. 段落 p
5. 头部 header
6. 脚部 footer
7. 主要内容 main
8. 次要内容 aside
9. 划分区域 div

## 全局属性

1. class 类
2. contenteditable 使此标签在网页上可编辑
3. hidden 隐藏标签内容
4. id 尽量不用
5. style 行间样式属性，可用 JS 操作之
6. tabindex tab 键选取顺序设置
   正数从小到大，0 为最后选取，-1 为不选取
7. title 全部内容，可配合文本溢出省略号使用

## 常用内容标签

1. ol + li 有序列表
2. ul + li 无序列表
3. dl + dt + dd
   dt 描述对象，dd 描述内容
4. pre 使标签内的 tab，回车，空格，按实际显示
5. hr 横线
6. br 换行
7. a 超链接
8. em 强调（语气）
9. strong 强调（内容）
10. code 标签里写代码
11. quote 内联引用，没啥默认样式
12. blockquote 块级引用，默认样式换行缩进
