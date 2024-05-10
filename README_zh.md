# .NET和人工智能资源精选列表
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

如果您有兴趣在.NET中使用人工智能（AI），这里有一系列示例、教程、SDK和视频帮助您入门并深入理解。目前涵盖的主题包括生成式人工智能（GenAI）和大型语言模型（LLMs）。

灵感来自 [frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks)、[ruby-bookmarks](https://github.com/dreikanter/ruby-bookmarks)、[awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning)、[awesome-generative-ai](https://github.com/steven2358/awesome-generative-ai) 和 [awesome-dotnet](https://github.com/quozd/awesome-dotnet) 等的启发。

欢迎贡献内容！请先查看[贡献指南和质量标准页面](CONTRIBUTING.md)。如果您发现这里的内容/链接有问题，也可以[报告问题](https://github.com/jmatthiesen/dotnet-ai-resources/issues)。如果您有一般性反馈，或者对特定示例有请求，也可以在 [讨论](https://github.com/jmatthiesen/dotnet-ai-resources/discussions) 部分提出。

# 许可证

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

注意：这个列表目前由[Jordan Matthiesen](https://github.com/jmatthiesen)在GitHub上托管，这里的内容包含并不意味着由我或我的雇主直接背书。我（和其他贡献者）发现这些项目有用，认为更广泛的.NET开发者社区会发现它们有帮助。欢迎提供反馈！

# 内容目录

- [入门](#getting-started)
- [新闻和社交媒体](#news--social-media)
- [社区和论坛](#community-and-forums)
- [教程和示例](#tutorials)
  - [使用本地模型](#working-with-local-models)
  - [处理数据/检索增强生成](#working-with-data)
  - [使用助手/代理](#using-assistants--agents)
  - [在不同工作负载/应用类型中包含AI](#include-ai-in-different-workloadsapp-types)
- [SDK](#sdks)
  - [Semantic Kernel](#semantickernel)
  - [协调器](#orchestrators)
  - [向量存储SDK](#vector-store-sdks)
- [AI服务](#ai-services)

# 入门

- [针对初学者的.NET中的生成式AI](https://youtube.com/playlist?list=PLdo4fOcmZ0oW_k4_eDTPWDLUVWz7A9y0M&si=c7B1fz4oQQYHEfy2) - 微软提供的入门课程，总结了生成式AI、机器学习（ML）之间的差异，以及如何入门。
  -  [AI 初学者系列的源代码](https://github.com/dotnet/beginner-series/tree/main/Artificial%20Intelligence%20and%20Machine%20Learning) - 上述介绍系列中的演示文稿和示例源代码。
- [.NET Conf 2023上的.NET开发者的生成式AI | .NET Conf 2023](https://youtu.be/yc0Zl_UXCY4?si=ko3xGqncKakU2xSt) - .NET Conf 2023会议：生成式AI入门 - 一个30分钟的介绍生成式AI的核心概念以及示例代码。
- [用.NET和Azure构建智能应用程序](https://www.youtube.com/watch?v=-3SrUqjq9Ic&list=PLdo4fOcmZ0oULyHSPBx-tQzePOYlhvrAU) - .NET Conf 2023会议，通过Azure OpenAI SDK，引导走 through OpenAI APIs using .NETthrough OpenAI APIs using .NET。
- [OpenAI与.NET示例笔记本](https://github.com/Azure-Samples/openai-dotnet-samples) | [公告帖子](https://devblogs.microsoft.com/dotnet/getting-started-azure-openai-dotnet/) - 大量示例笔记本（使用Polyglot笔记本），展示如何用.NET执行对OpenAI的各种操作。
- [系列博客；在.NET中开始使用OpenAI](https://devblogs.microsoft.com/dotnet/getting-started-azure-openai-dotnet/) - 博客系列概述了如何在.NET中使用OpenAI（系列其他帖子包括以下内容）：
  - [使用.NET开始使用OpenAI补全](https://devblogs.microsoft.com/dotnet/get-started-with-open-ai-completions-with-dotnet/) - 一个关于OpenAI补全的介绍，由模型如GPT生成的回复。
  - [通过提示工程提升你的GPT游戏](https://devblogs.microsoft.com/dotnet/gpt-prompt-engineering-openai-azure-dotnet/) - 引入提示工程，如何优化它们，以获得更相关的结果。
  - [在.NET中开始使用ChatGPT](https://devblogs.microsoft.com/dotnet/get-started-chatgpt-azure-dotnet/) - 描述了ChatGPT是什么以及核心概念，比如角色和聊天历史。

# 新闻和社交媒体

- [.NET + AI新闻来自.NET博客](https://devblogs.microsoft.com/dotnet/category/ai/) - 这是微软官方.NET博客的AI分类，您可以在这里找到.NET团队关于AI的最新帖子。

# 社区和论坛

- [.NET + AI on StackOverflow](https://stackoverflow.com/questions/tagged/.net+artificial-intelligence) - 在StackOverflow中关于`.net` + `artificial-intelligence`标签的搜索结果，一个发布问题给社区的好地方。
- [Azure AI社区](https://discord.com/invite/ByRwuEEgH4) - 有关Azure AI讨论的Discord社区。

# 教程和示例

## 教程

- [用AI构建你自己的课程助手](https://youtu.be/BRaltelZt6U?si=uuUvRc_9jSW4L601) "你在使用Azure OpenAI服务构建Copilot应用吗？你理解Copilot Stack的概念吗？在这次会议中，我们将使用Semantic Kernel构建您的第一个基于Copilot Stack的Copilot应用程序。" - 由Luis Quintanilla（微软）和Kinfey Lo（微软）主持
- [.NET Semantic Kernel 教程: 从零到浣熊英雄](https://www.youtube.com/playlist?list=PLPK0YODPQ5naaUwDNFay0mlRwaV_AbrX6) - 此视频教程系列，展示了如何使用Azure OpenAI、.NET、语义内核（Semantic Kernel）和OpenTelemetry创建一个生产就绪的大型语言模型（LLM）工具。

## 参考应用程序

- [Azure Search with OpenAI - C#示例](https://github.com/Azure-Samples/azure-search-openai-demo-csharp/) - [文档](https://learn.microsoft.com/dotnet/azure/ai/get-started-app-chat-template?tabs=github-codespaces) | [公告帖子](https://devblogs.microsoft.com/dotnet/transform-business-smart-dotnet-apps-azure-chatgpt/) ChatGPT + 企业数据与Azure OpenAI和认知搜索（.NET）
- [eShop](https://github.com/dotnet/eShop/)

## 使用本地模型

- [Torchsharp-phi](https://github.com/LittleLittleCloud/Torchsharp-phi) - 一个基于 [Torchsharp](https://github.com/dotnet/TorchSharp) 实现的Phi模型。
- [使用TorchSharp操作Llama2](https://github.com/LittleLittleCloud/Torchsharp-llama) -一个基于 [Torchsharp](https://github.com/dotnet/TorchSharp) 实现的llama-2模型。

## 使用多模态模型

- [使用Azure OpenAI服务生成图像](https://learn.microsoft.com/en-us/azure/ai-services/openai/dall-e-quickstart?tabs=dalle3%2Ccommand-line&pivots=programming-language-csharp) - 快速入门教程，展示如何使用Azure OpenAI SDK for C#来使用DALL-E生成图像。
- [使用AI生成图像，使用Stable Diffusion、C#和ONNX运行时](https://devblogs.microsoft.com/dotnet/generate-ai-images-stable-diffusion-csharp-onnx-runtime/) - 关于如何使用ONNX运行时和.NET访问Stable Diffusion模型来生成图像的概述

## 处理数据

- [用.NET揭开检索增强生成功能的神秘面纱](https://devblogs.microsoft.com/dotnet/demystifying-retrieval-augmented-generation-with-dotnet/) - 关于如何在.NET中用称为检索增强生成的概念处理数据的详细指南。
- [用Redis让.NET智能应用更智慧以及一致](https://devblogs.microsoft.com/dotnet/redis-makes-intelligent-apps-smarter-and-consistent/) 关于如何将Redis运用成智能应用的多功能数据存储。例如检索增强生成，向量搜索查询， 语义缓存
- [AugmentR](https://github.com/bradygaster/AugmentR) - 一个示例聊天机器人，展示了如何在.NET Aspire项目中使用Semantic Kernel，通过公共互联网URL的数据增强聊天。
- [Vector Search AI助手](https://github.com/Azure/Vector-Search-AI-Assistant/tree/cognitive-search-vector) - 演示如何结合来自CosmosDB的数据，并通过认知搜索进行查询，创建AI搜索助手的应用程序。
- [使用MongoDB的Vector Search AI助手](https://github.com/Azure/Vector-Search-AI-Assistant-MongoDBvCore) - 演示如何结合来自Azure CosmosDB for MongoDB的数据，并通过Azure OpenAI服务进行查询的应用程序。
- [Azure 上的检索增强生成示例](https://github.com/microsoft/AzureDataRetrievalAugmentedGenerationSamples/) - 包括许多 C# 示例，演示如何使用 CosmosDB + MongoDB 或 NoSQL。


## 使用 Assistants/Agents

- [Azure OpenAI：OpenAI助手客户端库](https://learn.microsoft.com/en-us/dotnet/api/overview/azure/ai.openai.assistants-readme?view=azure-dotnet-preview) - **[预发布]** Azure OpenAI SDK中OpenAI助手支持的参考文档，包括示例代码。

## 在不同工作负载/应用类型中包含AI

### NET MAUI - 移动开发
- [教程：使用 .NET MAUI 和 ChatGPT 创建推荐应用](https://learn.microsoft.com/en-us/windows/apps/windows-dotnet-maui/tutorial-maui-ai) - 指导教程，介绍如何创建适用于 ChatGPT 的简单 .NET MAUI 应用程序。
- [快速入门：将 DALL-E 添加到 .NET MAUI Windows 桌面应用](https://learn.microsoft.com/en-us/windows/apps/windows-dotnet-maui/dall-e-maui-windows) - 指导教程，演示如何创建使用 DALL-E 生成映像的简单 .NET MAUI 应用程序。


### Teams

- [.NET Conf 2023上使用Teams Toolkit和.NET的AI库构建带有生成式AI的机器人 | .NET Conf 2023](https://youtu.be/E6sEr3OrwgA?si=VmL5yUr3B21yU83u) - 如何为Microsoft Teams创建使用生成式AI和.NET的机器人。
- [使用Azure AI Search和.NET，为Copilot for Microsoft 365上的外部数据启用混合搜索（向量+语义）](https://adoption.microsoft.com/en-us/sample-solution-gallery/sample/officedev-copilot-for-m365-plugins-samples-msgext-doc-search-csharp/) - 微软示例展示如何在Teams消息扩展中整合Azure Search。

# SDK

## Semantic Kernel
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) - 微软构建的SDK，允许您“构建可以调用现有代码的代理”。为在.NET中工作提供了本地支持。
- [Semantic Kernel Cookbook](https://github.com/microsoft/SemanticKernelCookBook) - 使用语义内核实现常见任务的一组示例，以及可供 .NET 开发人员使用的多语言笔记本。
## 协调器


- [LangChain](https://github.com/tryAGI/LangChain/) **[非官方]** -.NET中广受欢迎的LangChain Python项目的实现。注意：目前它处于早期状态，正在寻找贡献者！

## 向量存储SDK

- [NRedis Stack .NET SDK](https://github.com/redis/NRedisStack) - 用Redis做向量搜索的.NET开发工具库
- [Redis OM for .NET](https://redis.io/docs/latest/integrate/redisom-for-net/) - 用Redis做对象搜索和语义缓存的.NET开发框架
- [Milvus C# SDK](https://milvus.io/docs/v2.2.x/install-csharp.md) - 用于与Milvus向量DB解决方案一起工作的.NET SDK。
- [Pinecone](https://github.com/neon-sunset/Pinecone.NET) - **[非官方]** 社区支持的SDK，用于与Pinecone向量DB一起工作。
- [Qdrant .NET SDK](https://github.com/qdrant/qdrant-dotnet) - SDK用于与Qdrant向量DB一起工作。
- [Weaviate](https://github.com/Unipisa/WeaviateNET) - [非官方] 社区支持使用 Weaviate vector DB 的 SDK。

## 人工智能服务

- [Azure OpenAI](https://learn.microsoft.com/en-us/azure/ai-services/openai/) - Azure OpenAI服务的概览，包括用于.NET的[快速开始示例](https://learn.microsoft.com/en-us/azure/ai-services/openai/chatgpt-quickstart?tabs=command-line%2Cpython&pivots=programming-language-csharp)。
- [Azure OpenAI服务示例](https://github.com/Azure-Samples/openai/) - 演示如何使用Azure OpenAI SDK的示例笔记本，许多示例为C#/.NET的Polyglot Notebooks。
- [适用于OpenAI GPT引擎的Azure函数绑定](https://github.com/Azure/azure-functions-openai-extension) - **[开发中]** Azure函数中新的OpenAI绑定的非常早期的评审，包括对C#的支持。
