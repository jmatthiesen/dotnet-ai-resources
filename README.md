# A curated list of .NET + AI resources

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
- [Online courses](#online-courses)
- [Tutorials and Samples](#tutorials)
  - [Working with Local Models](#working-with-local-models)
  - [Using Multi-modal models (images/video/text)](#multi-modal)
  - [Working with Agents](#working-with-agents)
  - [Working with Data / Retrieval-Augmented-Generation)](#working-with-data)
- [SDKs](#sdks)
  - [Orchestrators](#orchestrators)
  - [Vector Stores](#vector-store-sdks)

- [AI Services](#ai-services)

# Getting Started

- [Generative AI with .NET for Beginners](https://youtube.com/playlist?list=PLdo4fOcmZ0oW_k4_eDTPWDLUVWz7A9y0M&si=c7B1fz4oQQYHEfy2)
- [Generative AI for the .NET Developer | .NET Conf 2023](https://youtu.be/yc0Zl_UXCY4?si=ko3xGqncKakU2xSt)
- [Building Intelligent Apps with .NET and Azure](https://www.youtube.com/watch?v=-3SrUqjq9Ic&list=PLdo4fOcmZ0oULyHSPBx-tQzePOYlhvrAU)
- [OpenAI with .NET Samples Notebook](https://github.com/Azure-Samples/openai-dotnet-samples) | [Announcement Post](https://devblogs.microsoft.com/dotnet/getting-started-azure-openai-dotnet/)
- [Get started with ChatGPT in .NET](https://devblogs.microsoft.com/dotnet/get-started-chatgpt-azure-dotnet/)
- [Level up your GPT game with prompt engineering](https://devblogs.microsoft.com/dotnet/gpt-prompt-engineering-openai-azure-dotnet/)
- [Get started with OpenAI Completions with .NET](https://devblogs.microsoft.com/dotnet/get-started-with-open-ai-completions-with-dotnet/)

# News & Social media

- [.NET + AI news from the .NET Blog](https://devblogs.microsoft.com/dotnet/category/ai/)

# Community and Forums

- [.NET + AI on StackOverflow](https://stackoverflow.com/questions/tagged/.net+artificial-intelligence)
- [Azure AI Community](https://discord.com/invite/ByRwuEEgH4) Discord community for discussions about Azure AI.

# Online Courses

- [Generative AI for .NET Developers with Google AI](https://www.linkedin.com/feed/update/urn:li:activity:7137936525010354176/)

# Tutorials and Samples

## Tutorials

- [Build your own Course Assistant with AI](https://youtu.be/BRaltelZt6U?si=uuUvRc_9jSW4L601) "Are you using Azure OpenAI Service to build Copilot applications? Do you understand the concept of Copilot Stack? In this session we will use Semantic Kernel to build your first Copilot application based on Copilot Stack." - Hosted by Luis Quintanilla (Microsoft) and Kinfey Lo (Microsoft)
- [Coding a drone using .NET & ChatGPT AI and flying in mixed reality](https://youtu.be/5ChGYf10z1M?si=oxHXQyO60EEzsxE6) - Zaid Zaim
- [Building generative AI powered bots with Teams Toolkit and AI library for .NET | .NET Conf 2023](https://youtu.be/E6sEr3OrwgA?si=VmL5yUr3B21yU83u)
- [Start your AI and .NET Adventure with #30DaysOfAzureAI](https://www.youtube.com/watch?v=567890)

## Reference Applications

- [Azure Search with OpenAI - C# Sample](https://github.com/Azure-Samples/azure-search-openai-demo-csharp/) - [Documentation](https://learn.microsoft.com/dotnet/azure/ai/get-started-app-chat-template?tabs=github-codespaces) | [Announcement Post](https://devblogs.microsoft.com/dotnet/transform-business-smart-dotnet-apps-azure-chatgpt/) ChatGPT + Enterprise data with Azure OpenAI and Cognitive Search (.NET) 
- [eShop Reference Application](https://github.com/dotnet/eShop/)
  
## Working with Local Models

- [Using Phi2 with Torchsharp](https://github.com/LittleLittleCloud/Torchsharp-phi)
- [Using Llama2 with Torchsharp](https://github.com/LittleLittleCloud/Torchsharp-llama)

## Using Multi-modal Models

- [Generate images with AI using Stable Diffusion, C#, and ONNX Runtime](https://devblogs.microsoft.com/dotnet/generate-ai-images-stable-diffusion-csharp-onnx-runtime/)

## Working with Agents

## Working with Data

- [Demystifying Retrieval Augmented Generation with .NET](https://devblogs.microsoft.com/dotnet/demystifying-retrieval-augmented-generation-with-dotnet/)
- [AugmentR](https://github.com/bradygaster/AugmentR) - An example chat bot demonstrating the use of Semantic Kernel in a .NET Aspire project, augmenting chats with data from public internet URLs.
- [Vector Search AI Assistant](https://github.com/Azure/Vector-Search-AI-Assistant/tree/cognitive-search-vector) - Demo app showing how to combine data from CosmosDB, with Azure OpenAI Services and queries against cognitive search to create an AI search assistant.
- [Vector Search AI Assistant with MongoDB](https://github.com/Azure/Vector-Search-AI-Assistant-MongoDBvCore) - Demo app showing how to combine data from Azure CosmosDB for MongoDB, with queries against Azure OpenAI Services. 

# SDKs

## Orchestrators

- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) - SDK built by Microsoft that lets you "build agents that can call your existing code." Provides native support for working in .NET.
- [LangChain](https://github.com/tryAGI/LangChain/) **[Unofficial]** - .NET implementation of the popular LangChain Python project. Note: Currently it's in an early state, and looking for contributors!
  
## Vector Store SDKs

- [Milvus C# SDK](https://milvus.io/docs/v2.2.x/install-csharp.md) - A .NET SDK for working with the Milvus vector DB solution.
- [Qdrant .NET SDK](https://github.com/qdrant/qdrant-dotnet) - SDK for working with the Qdrant vector DB.
- [Pinecone](https://github.com/neon-sunset/Pinecone.NET) - **[Unofficial]** Community supported SDK for working with the Pinecone vector DB.

## AI Services

- [Azure OpenAI](https://learn.microsoft.com/en-us/azure/ai-services/openai/)
- [Azure AI Services](https://learn.microsoft.com/azure/ai-services/)
- [Azure OpenAI Service Samples](https://github.com/Azure-Samples/openai/) - Contains many samples in C#/.NET as Polyglot Notebooks


