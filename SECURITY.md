# Security Policy · 安全策略

## 支持范围

本账号下的开源项目均为个人项目，按「现状」提供。欢迎负责任地报告安全问题。

| 项目类型 | 是否接受安全报告 |
| :--- | :---: |
| 数据管线 / Agent / 站点（ai-daily, aiscan, trending-radar, reverse-radar, fin-intel-agent 等） | ✅ |
| 学习资料合集（AI-LLM-Agent-Learning） | ✅ |
| 已归档仓库 | ❌ |

## 报告方式

请**不要**通过公开 issue 披露安全问题。请使用 GitHub 的
[Private vulnerability reporting](https://docs.github.com/code-security/security-advisories/guidance-on-reporting-and-writing-information-about-vulnerabilities/privately-reporting-a-security-vulnerability)
（仓库 **Security** 标签页 → Report a vulnerability），或直接邮件联系。

请在报告中尽量包含：

- 受影响的仓库与版本 / commit
- 问题类型与复现步骤
- 可能的实际影响
- 你的联系方式（如需署名）

## 响应预期

这是个人维护的项目，无法承诺 SLA，但会在合理时间内确认收到并跟进。
确认修复后，如你愿意，会在 Release Notes / SECURITY 致谢中署名。

## 范围之外

- 依赖项的已知 CVE（请直接向上游报告）
- 无实际影响的自我 XSS、缺少头等纯加固建议
- 社会工程、钓鱼
