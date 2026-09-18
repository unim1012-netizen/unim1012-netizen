# UniΤέχνη

AI 应用开发爱好者 · 全栈实践者

专注于把 AI 工作流落地为可直接使用的 Web 应用——从 Coze 工作流设计、API 部署、跨域代理到 GitHub Pages 前端，全链路独立完成。

## 精选项目

### 求职助手 · AI 岗位匹配分析
[在线体验](https://unim1012-netizen.github.io/) · [项目仓库](https://github.com/unim1012-netizen/unim1012-netizen.github.io)

把 AI 求职匹配工作流从零构建为生产可用的网页应用：

- **功能**：输入三个顺位的求职意向（企业类型 + 意向职位）与个人经历，自动联网检索真实招聘信息，逐岗位完成匹配度评分、优势/差距分析与补充建议，生成完整求职分析报告
- **Coze 工作流**：基于 Coze AI 编程平台设计 14 节点工作流（意向解析 → 三路并行招聘检索 → 匹配分析 → 分支输出简历优化 / 面试建议 / 综合分析），输入参数为严格结构化枚举
- **部署架构**：Coze 工作流发布为 API 服务 → Cloudflare Workers 代理（解决浏览器 CORS 跨域、Token 仅存服务端）→ GitHub Pages 托管前端，全链路零服务器成本
- **技术栈**：HTML / CSS / JavaScript 单页应用 · Coze 工作流 API · Cloudflare Workers · GitHub Pages
- **工程细节**：异步任务执行与轮询、Markdown 报告渲染、响应式设计（桌面 / 移动）、错误码分级提示

## 技术方向

- AI 应用开发（Coze 工作流 / Agent / API 集成）
- Web 前端（原生 HTML/CSS/JS、响应式、可视化）
- 部署运维（GitHub Pages、Cloudflare Workers、GitHub Actions）
