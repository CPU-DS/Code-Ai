# 革新编程教学：基于大语言模型的AI编程助教设计与实践
本仓库是论文 **基于大语言模型的AI编程助教设计与实践** 的开源实现，包含论文中提到的 **在线评测系统** 和 **AI助教模型设计与评测** 模块。

## 📄 摘要
本文介绍了作者在 Python 程序设计与数据结构课程教学中实施的一项创新性改革。通过开发一个在线评测系统，并利用该系统收集的学生答题数据，对预训练大语言模型 Qwen2.5-Coder-7B-Instruct 进行了针对性微调。微调后的模型被嵌入到在线评测系统中，作为 AI 助教来辅助学生纠正编程错误。实验结果显示，相较于原始模型，微调后的 Qwen2.5-Coder-7B-Instruct 在纠正代码错误上的准确率提升了 26.17%，达到了 81.76%，超越了包括 GPT-4o mini 在内的云端大模型。此外，微调后的模型还优化了回答格式，使得反馈更加规范、有条理，有助于循序渐进地引导学生自主发现问题并解决问题，增强他们对课程的兴趣和信心。教学实践证明，这种基于 AI 的辅助教学方法能够显著改善学生的学习体验和成效，具有广泛的应用前景。

## 📁 仓库结构

本仓库将论文的相关资源分为多个模块，每个模块链接到独立的子仓库，方便维护和使用。

| 模块名称          | 描述                                                                                               | 链接                                                                                                   |
|------------------|--------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------|
| **系统** | 实现论文中的在线评测系统。                                                    | [CoderunnerEx](https://github.com/CPU-DS/CoderunnerEx)                                              |
| **模型**| 提供论文中的AI助教模型设计与评测。                                                    | [Code-AiHelper](https://github.com/CPU-DS/Code-AiHelper)                                             |

## 📊 实验结果

微调前、后的模型正确率分别为 55.59% 和 81.76% 。此外，还通过调用商用大模型 GPT-4o mini、DeepSeek-V2.5 以及 Qwen-Plus 的 API 接口，并按同样的方式在测试集上进行了评估，各模型的正确率分别为 76.03%、74.56% 和 70.83%。

## 📜 许可证
本项目基于 GNU General Public License v3.0 (GPL-3.0) 开源发布。

您可以在以下链接中查阅许可证的完整内容：[LICENSE](LICENSE)

## 📬 联系方式

若有问题或需要支持，请通过以下方式联系：
- [GitHub Issues](https://github.com/CPU-DS/Code-Ai/issues)
