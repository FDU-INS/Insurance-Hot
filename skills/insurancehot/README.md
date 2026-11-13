# insurancehot 技能

让 AI 工具用 [InsuranceHot](https://www.insurance-hot.com) 的实时资料回答保险业问题，并附原文出处。

| 文件 | 用途 |
| --- | --- |
| `SKILL.md` | 技能说明：何时使用、怎样用最少的调用回答、怎样引用原文、机构名怎么确认 |
| `references/orgs.md` | 机构清单：新闻 `org` 参数可用的机构，用于把用户说的名字对应到确切的机构 |
| `agents/openai.yaml` | Codex 等客户端的技能元数据 |

**安装**：最简单的方式是一句话接入，见[项目首页](../../README.md#oneline)。手动安装时，把整个 `insurancehot` 文件夹放进 AI 工具的技能目录，并按首页“手动接入”添加 MCP 服务。
