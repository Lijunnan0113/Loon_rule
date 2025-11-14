📘 Loon Config Repository

本仓库用于维护 Loon 配置文件、规则集、插件、模块以及相关扩展内容。
目标是构建一个结构清晰、可维护、可扩展的 Loon 配置生态，让分流、插件、脚本管理更加简单。

⸻

📁 仓库结构（建议）

configs/        # 完整 Loon 配置文件或模板
rules/          # 独立规则文件（分流 / 域名匹配等）
plugins/        # Loon 插件 (Plugin)
modules/        # Loon 模块 (Module)
scripts/        # 自动化脚本或辅助工具
README.md       # 当前说明文档

结构可根据你更新的内容调整，README 会保持兼容性描述。

⸻

📦 当前内容

✔ Rules（分流规则）
        •        Bybit Direct Rule
位于：rules/bybit_direct.conf
        •        用于 Bybit 相关域名的直连处理
        •        可作为远程规则拉取到 Loon 中使用

（后续加入新的规则文件后可继续在此添加）

⸻

🚀 在 Loon 中使用

添加远程规则
        1.        打开 GitHub 文件 → 点击 Raw
        2.        复制 Raw 链接
        3.        打开 Loon → 配置 → 远程规则
        4.        新增并粘贴链接 → 保存

添加插件 / 模块

方法相同，在 Loon 中选择对应的 “插件” 或 “模块” 入口添加远程链接即可。

⸻

🔧 未来内容计划
        •        更多主题规则（如流媒体、广告、加密货币等）
        •        Loon 插件模板集合
        •        Loon 模块集合
        •        自动更新工具（可选 GitHub Actions）
        •        完整 Loon 配置模板（含策略组）

⸻

📝 更新记录

内容将根据需求不定期更新。
具体变化请查看 Git 提交历史。

⸻

🤝 贡献

欢迎提交 PR 或 Issue，包括：
        •        新规则
        •        修复或优化现有配置
        •        添加插件或模块
        •        建议改进结构
⸻
