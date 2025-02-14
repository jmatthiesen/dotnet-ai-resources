# A curated list of .NET + AI resources
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Interested in working with AI in .NET? Here's a collection of samples, tutorials, SDKs, and videos to help you get started and go deeper. Topics covered currently include generative artificial intelligence (GenAI) and large language models (LLMs).

Inspired by [frontend-dev-bookmarks](https://github.com/dypsilon/frontend-dev-bookmarks), [ruby-bookmarks](https://github.com/dreikanter/ruby-bookmarks), [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning), [awesome-generative-ai](https://github.com/steven2358/awesome-generative-ai) and [awesome-dotnet](https://github.com/quozd/awesome-dotnet).

Contributions are always welcome! Please take a look at the [contribution guidelines and quality standard pages first](CONTRIBUTING.md). If you find issues with the content/links here, you can also [report them](https://github.com/jmatthiesen/dotnet-ai-resources/issues). If you have general feedback, or have a request for a specific sample, feel free to ask in the [Discussions](https://github.com/jmatthiesen/dotnet-ai-resources/discussions) section as well.

# License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

Note: This list is currently hosted on GitHub by me, [Jordan Matthiesen](https://github.com/jmatthiesen), and inclusion here doesn't imply a direct endorsement from me or my employer. I'm including projects I (and other contributors) find useful and think that the broader .NET developer community will find helpful. Feedback is welcome!

# Contents
- [Getting Started](#getting-started)
- [News & Social Media](#news--social-media)
- [Community and Forums](#community-and-forums)
- [Tutorials and Samples](#tutorials)
  - [Working with Local Models](#working-with-local-models)
  - [Working with Data / Retrieval-Augmented-Generation)](#working-with-data)
  - [Using Assistants/Agents](#using-assistantsagents)
  - [Include AI in different workloads/app types](#include-ai-in-different-workloadsapp-types)
- [SDKs](#sdks)
  - [Semantic Kernel](#semantic-kernel)
  - [AutoGen.Net](#autogennet)
  - [Orchestrators](#orchestrators)
  - [Vector Stores](#vector-store-sdks)
- [AI Services](#ai-services)

# Getting Started

- [AI for .NET Developers docs](https://learn.microsoft.com/en-us/dotnet/ai/) - The .NET + AI documentation site, providing an overview of AI concepts for .NET developers.
- [Generative AI with .NET for Beginners](https://youtube.com/playlist?list=PLdo4fOcmZ0oW_k4_eDTPWDLUVWz7A9y0M&si=c7B1fz4oQQYHEfy2) - An introductory course from Microsoft, summarizing the differences betwen Generative AI, Machine Learning (ML) and how you can get started with both.
  - [Source code for AI Beginner Series](https://github.com/dotnet/beginner-series/tree/main/Artificial%20Intelligence%20and%20Machine%20Learning) - The presentation and sample source from the above intro series.
- [.NET Conf: Focus on AI 2024 event](https://www.youtube.com/watch?v=0btB9W04y0Q&list=PLdo4fOcmZ0oX7Yg1cixIj6hXjz9C5MHJR) - A 2024 event hosted by the .NET team and friends. This event includes intros and some deep dives into a variety of .NET + AI related topics.
- [Building Intelligent Apps with .NET and Azure](https://www.youtube.com/watch?v=-3SrUqjq9Ic&list=PLdo4fOcmZ0oULyHSPBx-tQzePOYlhvrAU) - .NET Conf 2023 session with a guided walkthrough to using OpenAI APIs, through the Azure OpenAI SDK, with .NET.

# News & Social media

- [.NET + AI news from the .NET Blog](https://devblogs.microsoft.com/dotnet/category/ai/) - This is the AI category of the official .NET blog from Microsoft, where you can find the latest AI-specific posts from the .NET team.

# Community and Forums

- [.NET + AI on StackOverflow](https://stackoverflow.com/questions/tagged/.net+artificial-intelligence) - Search results for the `.net` + `artificial-intelligence` tags on StackOverflow, a great place to post questions to the community.
- [Azure AI Community](https://discord.com/invite/ByRwuEEgH4) - Discord community for discussions about Azure AI.

# Tutorials and Samples

## Tutorials

- [Build your own Course Assistant with AI](https://youtu.be/BRaltelZt6U?si=uuUvRc_9jSW4L601) "Are you using Azure OpenAI Service to build Copilot applications? Do you understand the concept of Copilot Stack? In this session we will use Semantic Kernel to build your first Copilot application based on Copilot Stack." - Hosted by Luis Quintanilla (Microsoft) and Kinfey Lo (Microsoft)
- [Semantic Kernel tutorial with dotnet: From Zero to Raccoon-Hero](https://www.youtube.com/playlist?list=PLPK0YODPQ5naaUwDNFay0mlRwaV_AbrX6) - A video series tutorial showing how to create a production-ready LLM tool using Azure OpenAI, .NET, Semantic Kernel and OpenTelemetry.

## Reference Applications

- [Azure Search with OpenAI - C# Sample](https://github.com/Azure-Samples/azure-search-openai-demo-csharp/) - [Documentation](https://learn.microsoft.com/dotnet/azure/ai/get-started-app-chat-template?tabs=github-codespaces) | [Announcement Post](https://devblogs.microsoft.com/dotnet/transform-business-smart-dotnet-apps-azure-chatgpt/) ChatGPT + Enterprise data with Azure OpenAI and Cognitive Search (.NET)
- [eShop Reference Application](https://github.com/dotnet/eShop/) - An eCommerce sample application built on .NET 8, .NET Aspire, and using Semantic Kernel to demonstrate an AI chat bot.
- [eShopSupport](https://github.com/dotnet/eShopSupport) - A sample customer support application for the eShop eCommerce solution. This sample demonstrates a variety of AI features: data generation, sentiment analysis, entity extraction, summarization, classification, as well as chat interactions.
  
## Working with Agents

- [Creative Writer - using Semantic Kernel, Aspire, and JS frontend](https://learn.microsoft.com/en-us/samples/azure-samples/aspire-semantic-kernel-creative-writer/aspire-semantic-kernel-creative-writer/)

## Working with Local Models

- [Using Phi2 with TorchSharp](https://github.com/LittleLittleCloud/Torchsharp-phi) - A sample demonstrating how to access the Phi2 model in your local system, using .NET with the help of the [TorchSharp](https://github.com/dotnet/TorchSharp) library.
- [Using Llama2 with TorchSharp](https://github.com/LittleLittleCloud/Torchsharp-llama) - This sample shows how to use the Llama2 model from your local system, using .NET with the help of the [TorchSharp](https://github.com/dotnet/TorchSharp) library.

## Using Multi-modal Models

- [Generate images with Azure OpenAI Servide](https://learn.microsoft.com/en-us/azure/ai-services/openai/dall-e-quickstart?tabs=dalle3%2Ccommand-line&pivots=programming-language-csharp) - Quick start tutorial showing how to use the Azure OpenAI SDK for C# to generate images using DALL-E.
- [Generate images with AI using Stable Diffusion, C#, and ONNX Runtime](https://devblogs.microsoft.com/dotnet/generate-ai-images-stable-diffusion-csharp-onnx-runtime/) - Overview of how you could access the Stable Diffusion model to generate images using .NET with the ONNX runtime

## Working with Data

- [Demystifying Retrieval Augmented Generation with .NET](https://devblogs.microsoft.com/dotnet/demystifying-retrieval-augmented-generation-with-dotnet/) - A detailed walkthrough of how to work with your data in .NET, using the concept known as Retrieval Augmented Generation.
- [Making AI powered .NET apps more consistent and intelligent with Redis](https://devblogs.microsoft.com/dotnet/redis-makes-intelligent-apps-smarter-and-consistent/) - A walkthrough on using Redis as the multi-purpose data store for intelligent apps. Highligint Retrievel Augmented Generation and Semantic Caching with Redis. 
- [AugmentR](https://github.com/bradygaster/AugmentR) - An example chat bot demonstrating the use of Semantic Kernel in a .NET Aspire project, augmenting chats with data from public internet URLs.
- [Vector Search AI Assistant](https://github.com/Azure/Vector-Search-AI-Assistant/tree/cognitive-search-vector) - Demo app showing how to combine data from CosmosDB, with Azure OpenAI Services and queries against cognitive search to create an AI search assistant.
- [Vector Search AI Assistant with MongoDB](https://github.com/Azure/Vector-Search-AI-Assistant-MongoDBvCore) - Demo app showing how to combine data from Azure CosmosDB for MongoDB, with queries against Azure OpenAI Services.
- [Samples for Retrieval Augmented Generation on Azure](https://github.com/microsoft/AzureDataRetrievalAugmentedGenerationSamples/) - Includes many examples in C# showing how to work with CosmosDB + MongoDB or NoSQL.

### CosmosDB + AI

- [Build a Copilot app using Azure Cosmos DB, Azure OpenAI Service and Azure App Service](https://github.com/AzureCosmosDB/cosmosdb-nosql-copilot) - 

## Using Assistants/Agents

- [Getting started using Azure OpenAI Assistants with C#](https://learn.microsoft.com/en-us/azure/ai-services/openai/assistants-quickstart?tabs=command-line&pivots=programming-language-csharp) - **[Pre-release]** A walkthrough showing how to use AI assistants with the Azure OpenAI SDK and C#.

- [AntRunner](https://github.com/douglasware/antrunner) - A complete set of .NET tools for creating and using Open AI and Azure Open AI Assistants with support for vector stores, code interpreter files, and function calling with local .NET functions and REST APIs with auth.

## Include AI in different workloads/app types

### ASP.NET Core

- [AI Chat App Quickstart using ASP.NET Core and a Blazor frontend](https://github.com/Azure-Samples/ai-chat-quickstart-csharp/) - Includes support for working with OpenAI models, local models, models available through GitHub Models, and Azure AI Model Catalog.

### .NET MAUI - Mobile Development

- [Tutorial: Create a recommendation app with .NET MAUI and ChatGPT](https://learn.microsoft.com/en-us/windows/apps/windows-dotnet-maui/tutorial-maui-ai) - Guided tutorial walking through how to create a simple .NET MAUI application that works with ChatGPT.
- [Quickstart: Add DALL-E to your .NET MAUI Windows desktop app](https://learn.microsoft.com/en-us/windows/apps/windows-dotnet-maui/dall-e-maui-windows) - Guided tutorial walking through how to create a simple .NET MAUI application that generates images using DALL-E.

### Teams

- [Building generative AI powered bots with Teams Toolkit and AI library for .NET | .NET Conf 2023](https://youtu.be/E6sEr3OrwgA?si=VmL5yUr3B21yU83u) - How to create bots for use in Microsoft Teams, using generative AI and .NET.
- [Enable Hybrid Search (Vector + Semantic) for your external data on Copilot for Microsoft 365 using Azure AI Search and .NET](https://adoption.microsoft.com/en-us/sample-solution-gallery/sample/officedev-copilot-for-m365-plugins-samples-msgext-doc-search-csharp/) - Microsoft sample showing how to integrate Azure Search in a Teams message extension.

# SDKs

## AutoGen.Net

- [AutoGen.Net](https://microsoft.github.io/autogen-for-net/) - Official .NET implementation of the [AutoGen](https://microsoft.github.io/autogen/) python project. AutoGen is a multi-agent conversation framework built by MS Research that allows you to easily construct multi-agent conversation and workflows.

## Azure AI Inference SDK

- [Introducing the Azure AI Inference SDK](https://devblogs.microsoft.com/dotnet/azure-ai-model-catalog-dotnet-inference-sdk/) - This SDK lets you easily access and use a wide range of AI models from the Azure AI Model Catalog for inference tasks like chat.

## Microsoft.Extensions.AI

- [Microsoft.Extensions.AI Source on GitHub](https://github.com/dotnet/extensions/tree/main/src/Libraries/Microsoft.Extensions.AI)
- [Introducing Microsoft.Extensions.AI preview](https://devblogs.microsoft.com/dotnet/introducing-microsoft-extensions-ai-preview/) - A set of core .NET libraries developed in collaboration with developers across the .NET ecosystem, including Semantic Kernel. These libraries provide a unified layer of C# abstractions for interacting with AI services, such as small and large language models (SLMs and LLMs), embeddings, and middleware.
- [Samples for Microsoft.Extensions.AI](https://github.com/dotnet/extensions/tree/main/src/Libraries/Microsoft.Extensions.AI)

## OllamaSharp

- [OllamaSharp source and docs](https://github.com/awaescher/OllamaSharp) - A library for working with [Ollama](https://www.ollama.com) to run AI models locally.

## OpenAI SDK

- [OpenAI SDK for .NET on GitHub](https://github.com/openai/openai-dotnet) - Includes the source, documentation, and samples for working with the library.
- [Announcing the OpenAI Library for .NET](https://devblogs.microsoft.com/dotnet/announcing-the-stable-release-of-the-official-open-ai-library-for-dotnet/) - Announcement blog post shared on the .NET blog.

## Semantic Kernel

- [Semantic Kernel Source on GitHub](https://github.com/microsoft/semantic-kernel)
- [Overview - Semantic Kernel](https://learn.microsoft.com/semantic-kernel/overview/) - A library built by Microsoft that lets you "build agents that can call your existing code." Provides native support for working in .NET.
- [Semantic Kernel Cookbook](https://github.com/microsoft/SemanticKernelCookBook) - A set of examples for achieving common tasks using Semantic Kernel, with Polyglot Notebooks available for .NET developers.

## Orchestrators

- [LangChain](https://github.com/tryAGI/LangChain/) **[Unofficial]** - .NET implementation of the popular LangChain Python project. Note: Currently it's in an early state, and looking for contributors!
  
## Vector Store SDKs

- [NRedis Stack .NET SDK](https://github.com/redis/NRedisStack) - A .NET SDK for working with Redis Enterprise for Vector Similarity Search
- [Redis OM for .NET](https://redis.io/docs/latest/integrate/redisom-for-net/) - A .NET SDK for Redis Search, Object Mapping, and Semantic Caching
- [Milvus C# SDK](https://milvus.io/docs/v2.2.x/install-csharp.md) - A .NET SDK for working with the Milvus vector DB solution.
- [Pinecone](https://docs.pinecone.io/reference/dotnet-sdk) - Official SDK for working with the Pinecone vector DB.
- [Qdrant .NET SDK](https://github.com/qdrant/qdrant-dotnet) - SDK for working with the Qdrant vector DB.
- [Weaviate](https://github.com/Unipisa/WeaviateNET) - **[Unofficial]** Community supported SDK for using the Weaviate vector DB.

# Tooling

- [Prompt files - using Prompty](https://www.prompty.ai) - An asset class and format for LLM prompts that aims to provide observability, understandability, and portability for developers.
  - [Add AI to Your .NET Apps Easily with Prompty](https://devblogs.microsoft.com/dotnet/add-ai-to-your-dotnet-apps-easily-with-prompty/) - A blog post with examples of how to use Prompty.

# AI Services

- [Azure OpenAI](https://learn.microsoft.com/en-us/azure/ai-services/openai/) - An overview of the Azure OpenAI service and including [Quick Start samples for .NET](https://learn.microsoft.com/en-us/azure/ai-services/openai/chatgpt-quickstart?tabs=command-line%2Cpython&pivots=programming-language-csharp).
- [Azure OpenAI Service Samples](https://github.com/Azure-Samples/openai/) - Sample notebooks demonstrating how to use the Azure OpenAI SDK, with may samples in C#/.NET as Polyglot Notebooks.
- [Azure Functions bindings for OpenAI's GPT engine](https://github.com/Azure/azure-functions-openai-extension) - **[In Development]** Very early review of new OpenAI bindings in Azure Functions, including support for C#.
