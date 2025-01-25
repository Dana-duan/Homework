1. 打开命令行窗口

- 按 Win键 + R,输入 cmd 并回车
- 或者在开始菜单搜索"命令提示符"

1. 基本目录导航命令:

`cd` - 切换目录

```Plain
cd Desktop        // 进入桌面文件夹
cd ..            // 返回上一级目录
cd \             // 返回根目录(C盘根目录)
cd C:\Users      // 进入指定完整路径
```

`dir` - 查看当前目录下的文件和文件夹

```Plain
dir              // 显示当前文件夹的内容
```

1. 基本文件操作:

`mkdir` (或 `md`) - 创建新文件夹

```Plain
mkdir test       // 创建名为test的文件夹
```

`copy` - 复制文件

```Plain
copy test.txt D:\backup     // 将test.txt复制到D盘的backup文件夹
```

`del` - 删除文件

```Plain
del test.txt     // 删除test.txt文件
```

1. 实用命令:

`cls` - 清屏

```Plain
cls              // 清除屏幕上的所有内容
```

`exit` - 退出命令行

```Plain
exit             // 关闭命令行窗口
```

1. 一些小技巧:

- 使用↑↓方向键可以查看之前输入过的命令
- 按 Tab 键可以自动补全文件名
- 输入命令的前几个字母后按 Tab 键可以循环显示所有可能的命令

1. 查看基本系统信息:

```Plain
systeminfo       // 显示电脑配置信息
ipconfig         // 显示网络配置信息
```

- 命令不区分大小写(CD 和 cd 是一样的)
- 如果文件路径中包含空格,要用引号括起来,如: `cd "Program Files"`
- 如果输入错误,可以按 Ctrl + C 终止当前操作