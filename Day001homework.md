今天分解的任务有三个: 

1.下载 typora windows版本:  https://typora.io/ (下载和安装很简单,自行完成)

2. 购买一个域名 (买最便宜的就行, 需要准备信用卡) https://dash.cloudflare.com (通过Google 搜索教程自行完成)
3. git和 github 的初次提交 

## Git和 Github 的基础使用

第一步：安装 Git for Windows

1. 访问 Git 官网 (https://git-scm.com/download/win) 下载 Git for Windows 安装包
2. 运行安装程序，大部分选项保持默认即可，但要注意以下几点：
   1. 选择默认的文本编辑器（推荐使用默认的 Vim 或选择 Visual Studio Code）
   2. 确保选中"Git from the command line and also from 3rd-party software"
   3. 选择"Use OpenSSH"选项
   4. 选择"Checkout Windows-style, commit Unix-style line endings"
   5. 选择"Use MinTTY"作为终端模拟器

第二步：配置 Git 基本信息

打开 Git Bash（可以在开始菜单找到），输入以下命令设置你的用户名(英文!)和邮箱：

git config --global user.name "你的名字"

git config --global user.email "你的邮箱地址"

第三步：创建 SSH 密钥

1. 在 Git Bash 中生成 SSH 密钥：

ssh-keygen -t ed25519 -C "你的邮箱地址"

1. 一路按回车使用默认设置。密钥会保存在 `C:\Users\你的用户名\.ssh` 目录下
2. 查看并复制公钥内容：

cat ~/.ssh/id_ed25519.pub

第四步：在 GitHub 上添加 SSH 密钥

1. 登录 GitHub 网站
2. 点击右上角头像 → Settings
3. 左侧菜单选择 "SSH and GPG keys"
4. 点击 "New SSH key"
5. 给密钥起个名字（比如"我的Windows电脑"）
6. 将刚才复制的公钥内容粘贴到 Key 文本框中
7. 点击 "Add SSH key" 保存

第五步：创建并克隆仓库

1. 在 GitHub 网站上创建新仓库：
   1. 点击右上角 "+" → New repository
   2. 填写**仓库名称**( 叫 **blog** )
   3. 选择是否添加 README 文件
   4. 点击 "Create repository"
2. 克隆仓库到本地：

git clone git@github.com:您的用户名/仓库名称.git

第六步：提交代码

1. 进入项目目录：

cd **blog**

1. 创建或修改文件(创建一个1.txt的目录 在里面输入今天的日期就行了)
2. 查看变更状态：

git status

1. 添加文件到暂存区：

git add .  # 添加所有文件

# 或者

git add 文件名  # 添加特定文件

1. 提交变更：

git commit -m "提交说明"

1. 推送到 GitHub：

git push origin main  # 或 master，取决于您的默认分支名称