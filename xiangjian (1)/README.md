# 乡见 - 助农网页项目

## 项目简介

“乡见”是一个连接城市消费者与乡村农户的助农平台。项目分为客户端和农户端：
- **客户端**：展示农产品，讲述农户故事。
- **农户端**：提供短剧剧本生成工具，助力农产品推广。

## 如何运行

### 方法一：直接打开

1. 找到项目文件夹 `xiangjian`。
2. 双击 `index.html` 文件，即可在默认浏览器中打开网站首页。
3. 点击首页上的“我是消费者”或“我是农户”按钮，即可进入相应页面。

### 方法二：使用本地服务器（推荐）

使用本地服务器可以避免一些因浏览器跨域策略导致的潜在问题。

#### 使用 Python：

1. 打开终端或命令提示符。
2. 导航到项目目录：
    ```bash
    cd /home/user/vibecoding/workspace/xiangjian
    ```
3. 运行以下命令启动服务器：
    - **Python 3.x**:
        ```bash
        python3 -m http.server 8000
        ```
    - **Python 2.x**:
        ```bash
        python -m SimpleHTTPServer 8000
        ```
4. 打开浏览器，访问 `http://localhost:8000`。

#### 使用 Node.js（需安装 `http-server`）：

1. 打开终端或命令提示符。
2. 导航到项目目录：
    ```bash
    cd /home/user/vibecoding/workspace/xiangjian
    ```
3. 运行以下命令启动服务器：
    ```bash
    npx http-server -p 8000
    ```
4. 打开浏览器，访问 `http://localhost:8000`。

## 项目结构

- `index.html`：网站首页。
- `client.html`：客户端页面。
- `farmer.html`：农户端页面。
- `assets/images/`：存放图片资源。

## 功能说明

- **首页**：介绍平台理念，提供入口。
- **客户端**：浏览农产品、查看农户故事。
- **农户端**：选择短剧模板，生成推广剧本。

## 技术栈

- HTML
- Tailwind CSS
- Lucide Icons