# Codify MCP Server

[Codify](https://codify.fun) 官方提供的 Model Context Protocol (MCP) 服务器客户端。该工具将 **MasterGo** 设计稿与 **Cursor / Windsurf / VS Code** 等 AI IDE 紧密连接。通过 MCP 协议，AI 可以直接读取画布节点、提取代码并同步设计变更。

---

## 🇨🇳 简体中文 (Simplified Chinese)

### 🚀 核心功能

- **设计转代码**: AI 直接拉取 MasterGo 画布节点代码，并根据规范转译为干净的组件。
- **双向同步**: 支持将本地代码变更全量同步回 MasterGo 画布。
- **资源托管**: 自动提取并上传设计稿中的图片资源到云端或本地。
- **原子化差异比对**: 精确比对本地代码与设计稿节点的结构差异。

### 📦 安装与更新

1.  前往 [Releases](https://github.com/uetop/mcp-releases/releases) 页面下载适合你系统的安装包（如 `.dmg` 或 `.exe`）。
2.  应用支持 **自动更新**，新版本发布时将收到提示。

### 🛠️ AI IDE 配置

启动应用并确保状态为 `RUNNING`。在 Cursor 等 IDE 的 MCP 设置中添加：

- **Type**: `sse` (或 `http`)
- **URL**: `http://localhost:8080`

---

## 🇺🇸 English Version

Codify MCP Server is an official tool that bridges **MasterGo** designs with AI-powered IDEs like **Cursor**, **Windsurf**, and **VS Code** via the Model Context Protocol (MCP).

### 🚀 Key Features

- **Design-to-Code**: AI retrieves real-time design nodes from MasterGo and converts them into production-ready code modules.
- **Bi-directional Sync**: Seamlessly push code changes back to the MasterGo canvas, ensuring design and development are always in sync.
- **Resource Management**: Automatically captures and hosts images or SVG assets extracted directly from design nodes.
- **Design Diffing**: Atomic-level comparison between local source code and design node structures.

### 📦 Installation & Updating

1.  Download the latest installer (`.dmg` for macOS, `.exe` for Windows) from the [Releases](https://github.com/uetop/mcp-releases/releases) page.
2.  The app features an **auto-updater**, ensuring you always stay current with the latest features and bug fixes.

### 🛠️ Configuration in AI IDEs

Ensure the Codify MCP Client is `RUNNING` (Default port: `8080`). In your IDE settings:

1.  Go to **MCP/SSE Settings**.
2.  Add a new server:
    - **Name**: `Codify`
    - **Type**: `sse` (or `http`)
    - **URL**: `http://localhost:8080`

### 🔐 Authentication

Obtain your **Access Key** from the [Codify Member Center](https://codify.fun) and configure it within the client's settings view.

---

© 2024 Codify AI. All rights reserved.
