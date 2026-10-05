# hub-index — OpenHanako 社区插件 & Skill 中央索引

本仓库是 [OpenHanako](https://github.com/liliMozi/openhanako) 插件市场的**社区重建版中央索引**。

原索引仓库 `hayou2002/openhanako-hub-index` 已被其所有者删除，导致市场前端 404。本仓库按照
[openhanako-hub-center 设计文档](https://github.com/hayou2002/openhanako-hub-center) 中的
元数据规范重建索引，收录当前仍活跃的生态插件与 Skill。

## 文件

| 文件 | 内容 |
|---|---|
| `plugins.json` | 插件元数据清单 |
| `skills.json` | Skill 元数据清单 |
| `categories.json` | 分类体系定义 |

## 插件使用方式

在 HanaAgent 插件市场（或任何读取本索引的市场前端）中，将索引仓库指向 `Meorny/hub-index` 即可。

## 收录与更新

- 收录标准：仓库根目录含 `manifest.json`（插件）或 `SKILL.md`（Skill）
- 数据由扫描脚本自动生成，抓取各仓库 manifest 元数据与 GitHub 仓库信息
- 欢迎提交 PR / Issue 登记新的插件仓库

## 收录清单

详见 `plugins.json` 与 `skills.json`。截至生成时收录 17 个插件、2 个 Skill。

## 许可

本仓库仅包含元数据清单，各插件/Skill 的许可以其各自仓库为准。
