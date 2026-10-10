# 通用学术文章写作 / Academic Writing

适用于任何领域的研究论文、文献综述、学术润色、翻译和汇报稿。采用清楚、自然、具体的学术措辞；核验引用；保留数字、公式与必要限定。默认避免夸张、破折号插入语和反复防御性解释。当前任务指令优先于默认偏好。

## 给支持skill安装的助手

将以下内容发送给对方：

> 请从 https://github.com/xuyuchen231-stack/academic-writing-skill 安装 write-academic-articles。skill路径为 plugins/academic-writing/skills/write-academic-articles。安装后使用它修改我的文章。

此请求只有在助手可以读取仓库、安装skill且拥有相应权限时才能执行。普通对话上传或仅说名称不保证安装成功。

## Codex插件市场来源

在支持该命令的Codex环境中：

```sh
codex plugin marketplace add https://github.com/xuyuchen231-stack/academic-writing-skill.git --sparse .agents/plugins --sparse plugins
```

然后在支持仓库市场的插件目录中选择此来源并安装 academic-writing。不同客户端的仓库市场功能可用性可能不同。

## 文件安装

将 plugins/academic-writing/skills/write-academic-articles 文件夹复制到支持的skill目录。例如项目中的 .agents/skills/write-academic-articles。安装后可明确调用 $write-academic-articles。

## 包含内容

- plugin.json：插件身份与版本。
- SKILL.md：完整写作规则。
- references：作者语言习惯与文献证据工作流。
- agents/openai.yaml：显示名称及调用提示。

不含私人聊天记录、API密钥、实验数据或账号凭据。安装本包不授予额外数据访问权限。文档渲染、实时文献检索和Zotero能力取决于使用环境。

这是可分发的仓库插件包，尚未提交或发布到OpenAI公开插件目录；无法保证仅按名称在所有账号中发现。
