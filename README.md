# 🌐 my-homepage

A minimalist, high-performance personal portfolio and tech blog built with a Command-Line Interface (CLI) Development Agent, inspired by the pure-text philosophy of **Andrej Karpathy's** personal homepage.

这是一个受到 Andrej Karpathy 个人主页纯文本、极简主义哲学启发而构建的个人主页与技术博客。本项目完全采用 Linux 命令行生态（WSL2 Ubuntu）配合 CLI Agent（Aider + DeepSeek）协作开发完成。

---

## 🎨 Design Philosophy / 设计理念

- **Extreme Minimalism (极简至上):** 像素级致敬 `karpathy.ai`。去除一切冗余的复杂前端框架（No React/Vue, No Heavy JS），回归网页最初的纯粹与速度，让内容成为绝对的核心。
- **Infra-Minded Workspace (底座视角):** 按照标准的现代前端资产规范组织目录，代码结构干净、清晰、高可维护性。
- **Agent-Native Development (面向 AI 原生开发):** 探索利用大模型加持的命令行 Agent 工具进行高效的辅助式软件工程与快速迭代。

## 📂 Project Structure / 目录结构

```text
my-homepage/
├── index.html          # 个人主页入口（致敬 Karpathy 极简风）
├── blog.html           # 博客列表页（"Musings of a Computer Scientist"）
├── css/                # 样式资产
│   ├── style.css       # 主页样式
│   └── blog.css        # 博客页样式
├── assets/             # 静态资源库
│   ├── images/         # 个人头像、教育/工作履历 Logo (PNG/JPG)
│   └── icons/          # 社交媒体平台矢量图标 (SVG)
├── posts/              # 博客文章库（独立的纯净 HTML 页面）
│   ├── post1.html
│   └── post2.html
└── archive/            # 历史版本与开发草稿备份