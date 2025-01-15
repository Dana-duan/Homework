# Markdown 教程 (Typora版)

## 第一部分：认识 Markdown 和 Typora

### 什么是 Markdown？

Markdown 是一种简单的文本格式化方式，它让你专注于写作本身，而不是复杂的排版。

你不需要用鼠标点击各种按钮，只需要输入一些简单的符号，就能让文字变得有层次、有重点。

### 为什么选择 Typora？

Typora 是一个非常友好的 Markdown 编辑器，它的特点是：

- 所见即所得：你输入 Markdown 符号后，文本会立即显示最终效果
- 简洁的界面：没有复杂的按钮和选项，让你专注于写作
- 实时预览：不需要分屏查看源代码和预览效果

## 第二部分：基础语法教程

### 1. 标题的使用

在 Typora 中，你可以这样创建标题：

```Markdown
# 一级标题
## 二级标题
### 三级标题
```

实际操作：只需要输入 # 加空格，然后输入标题内容即可。在 Typora 中，你会立即看到文字变成标题样式。

![img](https://axka3c5sgp.feishu.cn/space/api/box/stream/download/asynccode/?code=YjIwMzY4NGY0ZDUzMmU0MzBkOTE1NzYyMDRhMWM3ZTFfV29vaXAydlZramxaSURQU1NHYmJuRk1DcDVsQTdOREVfVG9rZW46THR4UWJzWUM1b215Tzl4V2NyV2NHNjRRbm5VXzE3MzY4OTkxMzA6MTczNjkwMjczMF9WNA)

### 2. 文本强调

想要强调某些文字，你可以：

- 使用 *单个星号* 或 *单个下划线* 表示斜体
- 使用 **双星号** 或 **双下划线** 表示粗体
- 使用 ***三个星号*** 表示粗斜体

在 Typora 中的快捷操作：

- 选中文字后按 Ctrl+I (Mac: Cmd+I) 变成斜体
- 选中文字后按 Ctrl+B (Mac: Cmd+B) 变成粗体

### 3. 制作列表

无序列表：

```Markdown
- 第一项
- 第二项
  - 子项目
  - 另一个子项目
```

有序列表：

```Markdown
1. 第一步
2. 第二步
   1. 子步骤
   2. 另一个子步骤
```

实际操作：在 Typora 中，输入 - 或 1. 加空格后，就会自动创建列表。按 Tab 键可以创建子列表。

### 4. 插入链接和图片

链接：

```Markdown
[链接文字](网址)
例如：[访问百度](https://www.baidu.com)
```

图片：

```Markdown
![图片说明](图片地址)
例如：![风景照](images/landscape.jpg)
```

在 Typora 中：

- 可以直接拖拽图片到编辑器中
- 复制图片后直接粘贴也可以
- 右键点击图片可以进行图片管理

### 5. 表格制作

在 Typora 中创建表格特别简单：

```Markdown
| 姓名 | 年龄 | 职业 |
| ---- | ---- | ---- |
| 张三 | 25   | 工程师 |
| 李四 | 28   | 设计师 |
```

更简单的方式：

1. 按快捷键 Ctrl+T (Mac: Cmd+T)
2. 输入行数和列数
3. 就能自动创建表格

### 6. 代码展示

行内代码：使用反引号 ` 包裹代码

```Markdown
使用 `print("Hello World")` 输出文字
```

代码块：使用三个反引号 ``` 包裹，还可以指定语言

```Python
def hello():
    print("Hello, Markdown!")
```

在 Typora 中：

- 输入 ``` 后回车，可以创建代码块
- 在代码块的语言区域输入编程语言名称，可以启用语法高亮

## 第三部分：实用技巧

### 1. Typora 的实用快捷键

- Ctrl+/ (Mac: Cmd+/): 切换源代码模式
- Ctrl+Shift+L: 打开/关闭侧边栏
- Ctrl+数字: 快速创建对应级别的标题

### 2. 文件管理建议

- 为你的 Markdown 文件创建专门的文件夹
- 图片最好统一存放在项目的 images 文件夹中
- 定期备份你的文档

### 3. 写作建议

- 先搭建文章框架（用标题进行组织）
- 然后填充具体内容
- 最后进行排版和美化
- 适时使用预览模式检查效果

## 练习建议

1. 创建一个新的 Markdown 文件
2. 尝试写一篇简单的日记或博客
3. 在文章中尽量使用各种 Markdown 语法
4. 多使用快捷键，养成习惯

## 常见问题解答

### 为什么我的格式没有生效？

- 检查标记符号前后是否有空格
- 确认是否在正确的位置使用了正确的符号
- 尝试切换源代码模式查看原始文本