# 小泡狐桌面端文档站与官方发布主页（v2.1.5）

面向 **AI 开发工具（Gemini / ChatGPT / Claude / Cursor / Antigravity）、跨区域团队协作与高清流媒体工作流** 打造的 Windows 桌面智能网络客户端与桌面 AI 宠物伴侣项目。本仓库用于公开发布 **正式客户端发行校验信息（SHA256）、使用指南、常见连接异常排查文档与版本更新日志**。

![Latest Version](https://img.shields.io/badge/最新版本-v2.1.5-ec4899)
![Platform](https://img.shields.io/badge/系统支持-Windows%2010%2F11%20x64-0284c7)
![Trial Quota](https://img.shields.io/badge/新人体验-5GB%20%7C%2024%E5%B0%8F%E6%97%B6-10b981)
![Rule Engine](https://img.shields.io/badge/%E5%88%86%E6%B5%81%E5%BC%95%E6%93%8E-MetaCubeX%20.mrs-8b5cf6)

> 安全说明：为保护基础设施稳定性，本公开仓库仅承载官方门户入口导航、文档站页面与安装包校验清单，不包含后端业务脚本或私有服务器配置。

---

## 官方入口与下载通道

| 站点说明 | 官方访问地址 | 用途 |
| --- | --- | --- |
| 小泡狐主门户 | [https://xph-vip.pages.dev](https://xph-vip.pages.dev) | 账号免密登录、客户端直链下载、卡网商城 |
| 小泡狐容灾备站 | [https://xph-bak.pages.dev](https://xph-bak.pages.dev) | 主站点繁忙或波动时无缝切换入口 |
| 斯莫德专线门户（主 / 备） | [smolder-gate](https://smolder-gate.pages.dev) / [smd-bak](https://smd-bak.pages.dev) | 华盛顿与欧洲双核联动专线入口 |
| 咩咩专线门户（主 / 备） | [miemie-gate](https://miemie-gate.pages.dev) / [mie-bak](https://mie-bak.pages.dev) | 莫斯科 BGP 专线入口 |
| GitHub Pages 独立文档站 | [https://sketchsketch942008-star.github.io/Xiaopohu-Desktop/](https://sketchsketch942008-star.github.io/Xiaopohu-Desktop/) | 套餐对比、AI 连接排障指南、桌面宠物伴侣说明 |

---

## v2.1.5 官方安装包核验（强烈建议下载后比对哈希）

- **GitHub Releases 官方镜像**：[https://github.com/sketchsketch942008-star/Xiaopohu-Desktop/releases](https://github.com/sketchsketch942008-star/Xiaopohu-Desktop/releases)
- **标准文件名**：`Xiaopohu-Client-Windows-2.1.5-x64-Setup.exe`
- **精确体积**：`181,819,988` 字节（约 173.4 MB）
- **SHA256 校验值**：`ee9b6201fddc10424864e0d53d1269c99c5d41ef28c4b19c0eb795549017b68d`

在 Windows PowerShell 中可执行以下命令核验下载文件完整性：

```powershell
Get-FileHash .\Xiaopohu-Client-Windows-2.1.5-x64-Setup.exe -Algorithm SHA256
```

---

## 核心特性与新客体验说明

1. **新邮箱 10 秒免密领试用**
   - 首次通过邮箱验证码登录即可自动获得 **5 GB / 24 小时** 体验配额，客户端登录后全自动同步智能规则配置，无需手动复制订阅链接。
   - 后续按需选购套餐或兑换激活卡，**已剩流量（含免费赠送流量）与有效期均支持 100% 无损叠加顺延**。
2. **AI 开发者与流媒体精准分流**
   - 内置社区维护的 **MetaCubeX `.mrs` 分流规则集**，默认精确分流国内直连应用与海外 AI 工具（Antigravity、ChatGPT、Claude、Gemini 等），支持 24 小时规则热更新与自动容灾切换。
3. **内置互动式桌面 AI 宠物伴侣**
   - 支持换装展示、多姿态情感互动、悬浮网速/剩余流量监控以及上下文 AI 问答陪伴，在工作和学习时兼顾桌面陪伴感。
4. **卡网商城与首单倒送流量**
   - 客户端内嵌「卡网商城」，支持常用数字效率工具与账号秒级自动发卡；同一账号每购买一款从未享过首单礼遇的新商品，按实付金额**每 5 元赠送 +100 GB / +30 天小泡狐加速流量**。
5. **v2.1.5 新增「代理招募」体系**
   - 仅针对小泡狐专线开放；基础代理免费参与，受邀新买家 3 天内套餐消费可享 30% 流量与时长实时返利；高级代理享 50% 代理点返利、1:1 转泡泡点及工单审核折现。

---

## 四档标准套餐参考（1 泡泡点 = ¥1，全专线通用）

| 套餐名称 | 泡泡点价格 | 增加高速流量 | 增加有效时长 | 适用场景 |
| --- | --- | --- | --- | --- |
| 30天随享卡 | 2 泡泡点（¥2） | +100 GB | +30 天 | 轻量日常办公与文档检索 |
| 90天尊享卡 | 5 泡泡点（¥5） | +300 GB | +90 天 | AI 工具高频交互与 4K 流媒体 |
| 180天超值卡 | 15 泡泡点（¥15） | +1000 GB | +180 天 | 开发者长时间高并发工程与大模型调用 |
| 360天包年卡 | 25 泡泡点（¥25） | +2000 GB | +360 天 | 旗舰包年大流量重度用户 |

---

## 文档导航

- [项目主页与快速上手](index.html)
- [套餐对比与 Bubble Points 规则说明](plans.html)
- [AI 工具（Gemini / Claude / Cursor / Antigravity）连接与晚高峰排障指南](ai-troubleshooting.html)
- [小泡狐桌面 AI 宠物伴侣玩法与配置指南](vpet-companion.html)
- [版本历史与 SHA256 发布清单](changelog.html)
