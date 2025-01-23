## 重要更新
**2025-6-26**：新增视频教程，涵盖相关软件的安装与设置。

---

编程的重要性不言而喻，但对于普通人来说，学习编程的门槛较高，往往让人望而却步。ChatGPT 的出现，让“自然语言编程”成为可能，即使没有编程基础，也能通过简单的描述生成代码，极大地提升了效率。

本文将通过一个简单的案例，手把手教你如何使用 ChatGPT 编写 Python 代码，将 5 个 MP4 文件快速转换为 MP3 文件。

---

## 1. 安装 Python

Python 是目前最流行的编程语言之一，功能强大且免费。以下是 Windows 11 系统下的安装步骤：

### 1.1 下载 Python
访问 [Python 官方下载页面](https://www.python.org/downloads/) 并下载最新版本。

### 1.2 安装 Python
双击安装程序，勾选“Add Python.exe to PATH”选项，然后按照提示完成安装。

---

## 2. 安装 VS Code

VS Code 是由微软开发的一款免费代码编辑器，适合运行 ChatGPT 生成的代码。

### 2.1 下载 VS Code
访问 [VS Code 官方下载页面](https://code.visualstudio.com/) 并下载软件。

### 2.2 安装 VS Code
双击安装程序，按照提示完成安装。

### 2.3 安装中文插件
1. 打开 VS Code，点击左侧扩展图标。
2. 搜索 “Chinese”，安装中文语言包。
3. 重启软件，界面将切换为中文。

### 2.4 安装 Python 扩展
1. 打开 VS Code，点击左侧扩展图标。
2. 搜索 “Python”，点击安装。

---

## 3. 准备素材

### 3.1 素材准备
准备 5 个 MP4 文件，或自行下载素材。

### 3.2 获取文件夹地址
将 MP4 文件放入一个文件夹中，右键复制文件夹地址。例如：`C:\Users\Administrator\Desktop\好歌`。

---

## 4. 使用 ChatGPT 生成代码

在 ChatGPT 中输入以下提示词：

你现在是一位 Python 程序员。请写一段代码，将文件夹 `C:\Users\Administrator\Desktop\好歌` 中的所有 MP4 文件转换为 MP3 文件。


**注意**：将文件夹地址替换为你自己的文件夹路径。

---

## 5. 在 VS Code 中运行代码

### 5.1 新建 Python 文件
1. 打开 VS Code，点击“文件”→“新建文件”。
2. 保存文件到桌面，命名为 `101.py`。

### 5.2 安装 moviepy
1. 打开终端，输入以下命令并回车：
   
   pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple
   
2. 安装 moviepy：
   
   pip install moviepy
   

### 5.3 运行代码
1. 将 ChatGPT 生成的代码粘贴到 `101.py` 文件中。
2. 点击右上角的运行按钮，等待程序完成。

运行完成后，转换后的 MP3 文件将保存在文件夹中。

---

## 6. 小结

通过 ChatGPT 和 Python 的结合，即使没有编程基础，也能轻松实现自动化任务。掌握基础用法后，你可以尝试更多复杂的功能，例如批量处理文件、自动化办公等。

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bit.ly/bewildcard)