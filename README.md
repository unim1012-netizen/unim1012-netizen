# UniΤέχνη
AI 应用开发者 · SwiftUI / Web 全栈
把想法做成能直接用的小工具——从 macOS 原生 App、AI 工作流到 Web 前端，独立完成设计、开发与部署。

## 精选项目

### 求职助手 · AI 岗位匹配分析
[在线体验](https://unim1012-netizen.github.io/Job-Offer-Assistant/) · [项目仓库](https://github.com/unim1012-netizen/Job-Offer-Assistant)

输入求职意向与个人经历，自动联网检索真实招聘信息，逐岗位打分并输出匹配度分析报告。

- **全链路独立交付**：Coze 14 节点工作流 → Cloudflare Workers 跨域代理 → GitHub Pages 前端，零服务器成本
- **技术栈**：原生 HTML/CSS/JS 单页应用 · Coze Workflow API · Cloudflare Workers

### 桌面任务日历 · Desktop Task Calendar
[项目仓库](https://github.com/unim1012-netizen/Desktop-Task-Calendar)

macOS 原生本地任务日历：输入任务 → 拖进月历排期 → 边缘拖拽调整跨度，纯本地运行、无云端无遥测。

- **原生 SwiftUI**：标准 macOS 窗口手感，6 套完整主题 × 浅/深模式一键切换
- **交互核心**：月历拖拽排期——拖中间平移、拖左右边缘改起止日，按天吸附、跨周自动换行
- **技术栈**：SwiftUI · SwiftPM · macOS 13+

### Markdown 转换器 · macOS 拖放式文档转 Markdown
[项目仓库](https://github.com/unim1012-netizen/markdown-converter-macos)

把 PDF、Word、PPT、Excel 等文件直接拖到图标上，自动转换成同名 `.md` 文件，基于微软开源 markitdown 构建。

- **零门槛拖放**：AppleScript droplet 应用，无需打开终端；一次可拖多个文件，同名自动加 `_1` 不覆盖
- **一键构建**：`./build.sh` 自动安装依赖并编译成可拖放 App，MIT 开源
- **技术栈**：Python · AppleScript · microsoft/markitdown

## 技术方向
- AI 应用开发（Coze 工作流 / Agent / API 集成）
- macOS 原生开发（SwiftUI / 拖拽交互 / 多主题系统）
- Web 前端（原生 HTML/CSS/JS、响应式、可视化）
- 部署运维（GitHub Pages、Cloudflare Workers、GitHub Actions）
