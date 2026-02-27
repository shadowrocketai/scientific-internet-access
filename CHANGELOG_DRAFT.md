### 🔧 v1.3.1 Changes

**SKILL.md 全面重写**
- 交互流程改为一问一答数字选择，面向纯小白用户
- 触发词扩充：加入"上不了Google"、"怎么翻墙"、"有什么节点"等真实用户语言
- 根据设备自动推荐客户端（Windows→Clash / Mac→ClashX / iPhone→Shadowrocket / Android→v2rayNG）
- 新增用户行为日志记录（user_queries.log），用于体验优化
- 新增安全提醒：免费节点不建议登录敏感账号

**README 优化**
- 对话示例改为真实用户语言
- 品牌措辞统一：标语用"科学上网"，触发词保留"翻墙"
- 移除未上线产品描述

**仓库规范化**
- 添加 MIT LICENSE
- 添加 .gitignore
- 添加 CHANGELOG.md
- GitHub Actions 仅 tag 触发，不再每次 push 跑
