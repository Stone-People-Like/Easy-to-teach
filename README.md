# 项目简介

本仓库用于承载中等职业教育技能教材（精简版）相关教学资料，目标是用更精简、直观的形式替代传统纸质教材，方便在电脑上阅读、演示和更新。以提高同学们的成绩以及学习效率。

当前仓库主要包含以下三个版本的教学资料：

### 📂 常规概括版
适合日常学习和系统复习，保留了较详细的知识点描述和示例：
- `《网页设计基础》.md`：网页教程核心教学内容。
- `《Python程序设计基础》.md`：Python 编程基础教程。
- `《数字媒体技术应用》.md`：数字媒体技术相关教程。
- `《数据库基础》.md`：数据库基础知识教程。
- `《网络技术基础》.md`：计算机网络基础教程。
- `《计算机软硬件技术基础》.md`：计算机软硬件基础教程。
- `思维导图/` 目录：包含各课程的思维导图图片。

### 📂 超级精简版
内容高度浓缩，表格化处理，适合考前快速查阅和背诵：
- `《网页设计基础》（精简版）.md`：网页教程精简版。
- `《Python程序设计基础》（精简版）.md`：Python 编程基础精简版教程。
- `《数字媒体技术应用》（精简版）.md`：数字媒体技术精简版教程。
- `《数据库基础》（精简版）.md`：数据库基础精简版教程。
- `《网络技术基础》（精简版）.md`：计算机网络基础精简版教程。
- `思维导图/` 目录：包含各课程精简版的思维导图图片。

### 📂 可打印版
提供PDF格式的教学资料，适合打印阅读：
- `常规概括/` 目录：包含常规概括版的PDF文件。
- `超级精简/` 目录：包含超级精简版的PDF文件。

### 🔧 工具与资源
- `typora/` 目录：包含 Typora 相关工具。
  - `typora-setup-x64-1.9.5.exe`：Typora 的安装程序（Windows x64）。
  - `gen-typora-key_v1.0.1.exe`：Typora 的破解工具。
- `img/` 目录：包含文档中的各种图片资源。
- **项目地址**：
  - GitHub：[https://github.com/Stone-People-Like/Easy-to-teach](https://github.com/Stone-People-Like/Easy-to-teach)
  - Gitee（国内推荐）：[https://gitee.com/Stone-People-Like/Easy-to-teach](https://gitee.com/Stone-People-Like/Easy-to-teach)


# 使用 Typora 浏览教学内容 （推荐方式）
## 1. 安装 Typora

选择使用本仓库 `typora` 目录中的 `typora-setup-x64-1.9.5.exe`：

- 进入 `typora` 文件夹，双击安装程序完成下载之后请勿打开Typora；
- 双击运行 `typora` 文件夹下的 `gen-typora-key_v1.0.1.exe` 破解工具，等待一会后复制出现的序列号；
- 当出现网络连接失败后，询问是否切换国内服务器，点击是
- 随后激活成功，同时取消勾选自动更新和自动检查更新
- 一切使用行为仍需遵守 Typora 的许可协议，本仓库不对任何违反授权协议的使用方式负责。


## 2. 使用 Typora 打开本项目文档

Typora 安装完成后，可以通过以下方式打开教学资料：

1. 启动 Typora。
2. 在 Typora 中选择：
   - 菜单：`File` → `Open`（或中文界面中的“文件 → 打开”）
3. 找到本仓库所在目录，例如：
   - `C:\Users\admin\Desktop\教学精简版本`
4. 根据需要进入 **`常规概括版`** 或 **`超级精简版`** 文件夹。
5. 选择对应的 `.md` 文件（如 `《网页设计基础》（精简版）.md`）并打开。

此时你就可以：

- 以所见即所得的方式阅读整本“教材”；
- 在课堂演示时放大字号、切换主题，提升可读性；

# 线上方式来在线查看资料

## 1. 使用GitHub在线预览

1. 单击想要预览的文件夹（`常规概括版` 或 `超级精简版`）。
2. 点击文件即可实现在线预览。
3. 受网页端影响可能会出现图片显示问题还是推荐Typora线下预览。

## 2. 使用相关网站进行查看

1. 打开浏览器在网址中输入https://www.mylyq.icu
2. 点击课程列表即可在线查看资料
3. 受技术影响，网页端更新速度会慢于GitHub，如果想要最新资讯请关注本项目

# 将本项目部署到自己电脑上

这里的“部署”主要指：把本仓库完整拷贝到你自己的电脑上，并通过 Typora 或其他 Markdown 编辑器进行阅读和使用，而不是部署成网站或服务。

## 方式一：通过 Git 克隆仓库（推荐）

前提：电脑已安装 Git。

1. 打开命令行（PowerShell / CMD 等）。
2. 选择一个你希望存放资料的目录，例如：

   ```powershell
   cd C:\Users\admin\Desktop
   ```

3. 克隆仓库：

   ```powershell
   git clone https://github.com/Stone-People-Like/Easy-to-teach.git
   ```

4. 进入仓库目录：

   ```powershell
   cd Easy-to-teach
   ```

5. 进入 `常规概括版` 或 `超级精简版` 目录，用 Typora 打开对应文件即可开始使用。

之后如果远端仓库有更新，你可以在该目录下执行：

```powershell
git pull
```

即可同步最新内容。


## 方式二：直接从 GitHub/Gitee 网页下载压缩包

如果你不熟悉 Git，也可以直接下载 ZIP 压缩包：

### Gitee 下载（推荐）
1. 打开仓库地址：[https://gitee.com/Stone-People-Like/Easy-to-teach](https://gitee.com/Stone-People-Like/Easy-to-teach)
2. 点击橙色按钮 `克隆/下载` -> `下载 ZIP`。

### GitHub 下载
1. 打开仓库地址：[https://github.com/Stone-People-Like/Easy-to-teach](https://github.com/Stone-People-Like/Easy-to-teach)
2. 点击绿色按钮 `Code` -> `Download ZIP`。

3. 将下载得到的压缩包解压到任意目录，例如：  
   `C:\Users\你的用户名\Documents\教学精简版本`
4. 进入解压后的文件夹，找到 `常规概括版` 或 `超级精简版` 目录，用 Typora 打开文件即可。


## 方式三：在多台电脑之间同步

如果你希望在多台电脑上使用这套资料，可以采用以下方式：

- 使用 Git：
  - 每台电脑都 `git clone` 同一个仓库地址；
  - 在某一台电脑上修改内容并 `git commit` + `git push`；
  - 其他电脑上执行 `git pull` 同步更新。


# 版权与使用说明

- 教学内容文件仅用于教学演示和学习使用，不得用于商业贩卖或其他侵权用途。
- Typora 属于第三方商业软件，请严格遵守其官方授权协议，支持正版（虽然已经破解）。
- 本仓库属于23数媒2班&copy;陆云清所有，若发现问题请及时进行联系：19243004532@163.com
