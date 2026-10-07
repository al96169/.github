# .github

本仓库为 [@al96169](https://github.com/al96169) 账号下的**默认社区健康文件**仓库。

GitHub 会自动把这里的文件作为**所有未自带同名文件**的仓库的默认值：

| 文件 | 作用 |
|---|---|
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | 贡献指南：如何提 Issue、提 PR |
| [`SECURITY.md`](SECURITY.md) | 安全漏洞上报流程 |
| [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) | 行为准则 |
| [`ISSUE_TEMPLATE/`](ISSUE_TEMPLATE/) | Issue 模板（Bug 报告 / 功能建议） |
| [`PULL_REQUEST_TEMPLATE.md`](PULL_REQUEST_TEMPLATE.md) | PR 模板 |

> 某个仓库若自己提供同名文件，则以该仓库自己的为准（可覆盖此处的默认值）。

---

## 关于 wo-bot

[wo-bot](https://github.com/al96169/wo-bot-wiki) 是本账号下的**开源机器人控制平台**，
以 Jetson Nano 为机器人主控，配套网页 / App 远程控制、云端账号与信令服务。

| 仓库 | 职责 | 技术栈 |
|---|---|---|
| [wo-bot-control](https://github.com/al96169/wo-bot-control) | 机器人端核心服务：外设驱动、通信、状态管理 | Python 3.7+ / asyncio / OpenCV / GStreamer |
| [wo-bot-web-debug](https://github.com/al96169/wo-bot-web-debug) | Web 控制端：视频预览、遥控、语音喊话 | Vue 3 / TypeScript / WebRTC |
| [wo-bot-app](https://github.com/al96169/wo-bot-app) | 手机 App 客户端 | Flutter |
| [wo-bot-signal](https://github.com/al96169/wo-bot-signal) | 云端信令与授权服务器 | Node.js / TypeScript / coturn |
| [wo-bot-account](https://github.com/al96169/wo-bot-account) | 账号与设备授权（Logto OIDC + 管理后台） | NestJS / Prisma / Vue 3 / Docker |
| [wo-bot-market](https://github.com/al96169/wo-bot-market) | 软件包市场服务 | Python 3.9+（标准库） |
| [wo-bot-wiki](https://github.com/al96169/wo-bot-wiki) | 方案、协议与开发规范文档 | Markdown |

开发约定、架构说明与踩坑记录见 [wo-bot-wiki](https://github.com/al96169/wo-bot-wiki)；
其中 [AGENT.md](https://github.com/al96169/wo-bot-wiki/blob/main/AGENT.md) 是所有子仓库开发的必读文档。

## License

[MIT](LICENSE)
