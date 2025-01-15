## 任务一

1. 安装 Node.js：
- 访问官网 https://nodejs.org
- 下载左侧的 LTS 版本（长期支持版，更稳定）
- 运行安装包，一路点击"下一步"即可
- 安装完成后，打开命令行输入：
```bash
node -v    # 检查是否安装成功
npm -v     # 检查 npm 是否可用
```

2. 设置国内镜像源（推荐使用淘宝镜像源，速度快）：
```bash
# 查看当前源
npm config get registry

# 设置淘宝镜像源
npm config set registry https://registry.npmmirror.com
```

这样就完成了最基本的配置，之后就可以正常使用 npm 安装各种包了。



## 任务二

一个简单的步骤:

1. 全局安装 serve:
```bash
npm install -g serve
```

2. 创建一个简单的 html 文件:
```bash
# 创建一个文件夹
mkdir mysite
cd mysite

# 创建 index.html 内容如下:
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的网站</title>
</head>
<body>
    <h1>Hello from my phone!</h1>
    <p>这是我的第一个网站</p>
</body>
</html>
```

3. 启动服务器:
```bash
# 在 mysite 目录下运行
serve .
```

4. 查看访问地址:
- serve 会显示几个地址
- 找到类似 `http://192.168.1.100:3000` 的局域网地址
- 确保手机和电脑在同一个 WiFi 下
- 在手机浏览器输入这个地址就能访问了

也可以指定端口运行:
```bash
serve . -p 5000  # 使用 5000 端口
```

记住:
- 电脑和手机要在同一个 WiFi 下
- 如果有防火墙，需要允许对应端口的访问
- 默认端口是 3000，可以用 -p 参数修改