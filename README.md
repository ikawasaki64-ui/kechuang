# 课窗

**让每一页课件都能被理解、练习和追问。**

课窗是一款电脑端 AI 学习工作台。它把课件、讲解、随学练习和即时问答放在同一个界面。读到哪里，解释就跟到哪里；学到适合检验的地方，题目就在旁边出现；遇到不懂的概念，可以直接指着当前内容提问。

## 产品介绍

用户导入课件后，可以选择以下学习模式：

| 学习模式 | 中文名称 |
| --- | --- |
| Guided Learn | 引导学习 |
| Quick Review | 快速复习 |
| Class Companion | 课堂伴学 |
| Test Mode | 自测训练 |

左侧保存科目和课件，中间承载学习内容，右上题目区随阅读进度出现，右下问答区回答眼前的问题。未答完的题不会被下一题替换；答错后可以回到对应内容再看。

Review 服务于课件学习、练习与复盘；Live 服务于正在发生的课堂。两者可以切换，也可以用小窗或分屏配合。课窗还会为课件建议标题和科目，并留下学习操作、模型调用及费用对账记录，让学习过程可以回看和核查。

以上为项目作者提供的产品整体介绍。各历史版本的具体功能以对应发布说明和实际安装包为准；不表示上述功能均已在 v1 中验证。

## 下载与安装

1. 打开 [最新版本发布页](https://github.com/ikawasaki64-ui/kechuang/releases/latest)；历史版本见下方版本下载表。
2. 在 Assets 中下载对应版本的 Windows `.exe` 安装包。
3. 在 Windows 电脑上运行安装程序，按安装向导完成安装。
4. 启动课窗；如程序提示需要模型服务配置，请按该版本界面提示完成配置，再导入课件开始学习。

安装包的最低 Windows 版本、硬件要求、支持的课件格式及 v1 模型配置步骤尚未提供，后续将根据实际版本补充。

## v1 历史文件信息

| 项目 | 内容 |
| --- | --- |
| 发布标签 | `v1` |
| 下载文件名 | `kechuang-v1-windows.exe` |
| 原始文件名 | `课窗安装程序v1.exe` |
| 文件大小 | 36,340,224 字节（约 34.7 MiB） |
| SHA-256 | `C38D8F08EEF21224BAE16B511EE8FF5C9A71548EA3F51035D0EDB2E05866D047` |

下载文件仅调整了文件名，内容与原始安装包一致。发布标签依据原始文件名确定；安装包内置文件版本为 `0.0.0.0`。

可在 PowerShell 中校验下载文件：

```powershell
Get-FileHash -LiteralPath '.\kechuang-v1-windows.exe' -Algorithm SHA256
```

将结果与本页或发布附件 `SHA256SUMS.txt` 中的值对照。校验值用于确认文件内容一致，不代表运行或功能验收通过。

## 版本下载

| 顺序 | 版本 | 原始安装包 |
| --- | --- | --- |
| 1 | [v1](https://github.com/ikawasaki64-ui/kechuang/releases/tag/v1) | 课窗安装程序v1.exe |
| 2 | [v1.3](https://github.com/ikawasaki64-ui/kechuang/releases/tag/v1.3) | 课窗安装程序v1.3.exe |
| 3 | [v1.31](https://github.com/ikawasaki64-ui/kechuang/releases/tag/v1.31) | 课窗安装程序v1.31.exe |
| 4 | [v1.32](https://github.com/ikawasaki64-ui/kechuang/releases/tag/v1.32) | 课窗安装程序v1.32.exe |
| 5 | [v1.3.4](https://github.com/ikawasaki64-ui/kechuang/releases/tag/v1.3.4) | 课窗1.3.4安装程序.exe |
| 6 | [v1.3.5](https://github.com/ikawasaki64-ui/kechuang/releases/tag/v1.3.5) | 课窗v1.3.5安装程序.exe |
| 7 | [v1.3.5 引导学习修订版](https://github.com/ikawasaki64-ui/kechuang/releases/tag/v1.3.5-guided-learning) | 课窗v1.3.5安装程序-引导学习修订版.exe |
| 8 | [v1.3.6 11优化版](https://github.com/ikawasaki64-ui/kechuang/releases/tag/v1.3.6) | 课窗v1.3.6安装程序-11优化版.exe |

## 使用许可与商业授权

课窗采用[课窗非商业使用许可](LICENSE)。允许依许可进行非商业使用；**任何商业用途均须事先获得书面授权**，包括原版、修改版、衍生作品、收费服务和企业内部使用。修改、改名或重新打包不会消除商业限制。第三方组件仍适用其各自的许可。

商业授权联系：

- 邮箱：lnc20071017@163.com
- 备用邮箱：ikawasaki64@gmail.com
- 微信：`e_161019`
- **请先备注来意**，并说明使用主体、用途、修改与分发方式及收费方式。

本项目采用非商业许可；公开发布不等于授予商业使用权。

## 版本与反馈

本仓库用于发布课窗安装包、项目介绍及版本说明。安装包放在 [Releases](https://github.com/ikawasaki64-ui/kechuang/releases)，版本记录见 [CHANGELOG.md](CHANGELOG.md)。当前发布材料未包含项目源码。

历史版本已按原始顺序归档发布；同号修订包使用独立标签。1.3.6 仅发布 11优化版，其余 1.3.6 中间构建未发布。前几个没有更新说明的版本仅记录版本号；后续版本保留原始更新说明。

遇到问题可在 [Issues](https://github.com/ikawasaki64-ui/kechuang/issues) 中提供版本号、复现步骤和错误截图。提交截图或日志前，请移除 API Key、个人信息和私有课件内容。
