# 本地改动说明

本分支为 [krkr521/maibot-plugin-emoji-text-selection](https://github.com/krkr521/maibot-plugin-emoji-text-selection/tree/local/custom) 的本地定制快照。
原项目：[hsd221/maibot-plugin-emoji-text-selection](https://github.com/hsd221/maibot-plugin-emoji-text-selection)。
对照基线：`64cf00d0dae18fe0dd7ab36a860607a5364fc484`；整理日期：2026-11-13。

## 相对基线的主要改动

- 表情选择的 LLM 请求显式使用 temperature=0.7、max_tokens=256。
- 保留本地宿主兼容性声明，补齐上游已声明的 GPL-3.0-or-later 许可证全文。

## 安装与配置

```sh
git clone --branch local/custom https://github.com/krkr521/maibot-plugin-emoji-text-selection.git
```

将仓库放入 MaiBot 插件目录，按原说明安装依赖并在自己的实例中配置。插件 ID 和原作者署名保留，替换同 ID 插件前请备份。
本分支来自定制宿主环境。涉及扩展 RPC、Decision 或后台任务接口的能力需要对应宿主支持；不能据此认定与所有官方 MaiBot 版本兼容。

## 发布范围

保留原许可证及第三方署名。发布内容为源码、通用模板、文档和测试；不包含本机配置、配置备份、Cookie、访问令牌、语音样本、付款码、聊天记录、实际记忆或私有提交历史。
本地部署笔记已改写为通用说明，运行数据由安装者自行管理。
