

将下面的内容保存为 index.html,使用昨天的方式以网页形式打开 



```
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML入门教程</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            color: #333;
        }
        h1 {
            color: #2c3e50;
            text-align: center;
            border-bottom: 2px solid #eee;
            padding-bottom: 10px;
        }
        h2 {
            color: #3498db;
            margin-top: 30px;
        }
        .code-block {
            background-color: #f8f9fa;
            border-left: 4px solid #3498db;
            padding: 15px;
            margin: 15px 0;
            border-radius: 4px;
            overflow-x: auto;
        }
        .note {
            background-color: #fff3cd;
            border-left: 4px solid #ffc107;
            padding: 15px;
            margin: 15px 0;
            border-radius: 4px;
        }
        .example {
            border: 1px solid #ddd;
            padding: 15px;
            margin: 15px 0;
            border-radius: 4px;
        }
    </style>
</head>
<body>
    <h1>HTML入门教程 - 零基础学习指南</h1>

    <h2>1. HTML是什么？</h2>
    <p>HTML（HyperText Markup Language，超文本标记语言）是创建网页的标准标记语言。它描述了网页的结构，告诉浏览器如何显示内容。</p>

    <div class="note">
        <strong>小贴士：</strong>HTML不是编程语言，而是一种用于标记文档结构的标记语言。
    </div>

    <h2>2. HTML文档基本结构</h2>
    <div class="code-block">
        <pre>
&lt;!DOCTYPE html&gt;
&lt;html&gt;
&lt;head&gt;
    &lt;title&gt;网页标题&lt;/title&gt;
&lt;/head&gt;
&lt;body&gt;
    网页内容
&lt;/body&gt;
&lt;/html&gt;</pre>
    </div>

    <h2>3. 基本HTML标签</h2>
    <h3>3.1 标题标签</h3>
    <div class="code-block">
        <pre>
&lt;h1&gt;一级标题&lt;/h1&gt;
&lt;h2&gt;二级标题&lt;/h2&gt;
&lt;h3&gt;三级标题&lt;/h3&gt;
&lt;h4&gt;四级标题&lt;/h4&gt;
&lt;h5&gt;五级标题&lt;/h5&gt;
&lt;h6&gt;六级标题&lt;/h6&gt;</pre>
    </div>

    <div class="example">
        <h1 style="font-size: 24px;">一级标题</h1>
        <h2 style="font-size: 20px;">二级标题</h2>
        <h3 style="font-size: 18px;">三级标题</h3>
    </div>

    <h3>3.2 段落和文本格式化</h3>
    <div class="code-block">
        <pre>
&lt;p&gt;这是一个段落&lt;/p&gt;
&lt;strong&gt;粗体文本&lt;/strong&gt;
&lt;em&gt;斜体文本&lt;/em&gt;
&lt;br&gt;换行
&lt;hr&gt;水平线</pre>
    </div>

    <div class="example">
        <p>这是一个段落</p>
        <strong>粗体文本</strong><br>
        <em>斜体文本</em>
        <hr>
    </div>

    <h3>3.3 链接和图片</h3>
    <div class="code-block">
        <pre>
&lt;a href="https://www.example.com"&gt;这是一个链接&lt;/a&gt;
&lt;img src="image.jpg" alt="图片描述"&gt;</pre>
    </div>

    <div class="example">
        <a href="#">这是一个链接</a><br>
        <img src="/api/placeholder/200/100" alt="示例图片">
    </div>

    <h3>3.4 列表</h3>
    <div class="code-block">
        <pre>
&lt;!-- 无序列表 --&gt;
&lt;ul&gt;
    &lt;li&gt;项目1&lt;/li&gt;
    &lt;li&gt;项目2&lt;/li&gt;
&lt;/ul&gt;

&lt;!-- 有序列表 --&gt;
&lt;ol&gt;
    &lt;li&gt;第一项&lt;/li&gt;
    &lt;li&gt;第二项&lt;/li&gt;
&lt;/ol&gt;</pre>
    </div>

    <div class="example">
        <ul>
            <li>项目1</li>
            <li>项目2</li>
        </ul>
        <ol>
            <li>第一项</li>
            <li>第二项</li>
        </ol>
    </div>

    <h2>4. 实践建议</h2>
    <ul>
        <li>始终使用正确的HTML文档结构</li>
        <li>保持代码整洁，适当使用缩进</li>
        <li>确保标签正确闭合</li>
        <li>使用有意义的文件名和标签名</li>
        <li>经常测试你的代码</li>
    </ul>

    <div class="note">
        <strong>练习建议：</strong>
        <p>尝试创建一个简单的个人介绍页面，运用本教程中学到的各种标签。实践是最好的学习方式！</p>
    </div>

    <h2>5. 下一步学习</h2>
    <ul>
        <li>学习CSS来美化你的网页</li>
        <li>了解更多HTML5新特性</li>
        <li>学习JavaScript为网页添加交互功能</li>
        <li>探索响应式网页设计</li>
    </ul>
</body>
</html>
```



总结出如下的标题分别有哪些:



HTML的基本概念介绍

HTML文档的基本结构

常用HTML标签的介绍和示例，包括：

- 标题标签
- 段落和文本格式化
- 链接和图片
- 列表（有序和无序）