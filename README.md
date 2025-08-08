# 📘 MCP Learning Cookbook and Notes

Welcome to my personal learning repository for **Model Context Protocol (MCP)** and related **Generative AI (GenAI)** concepts. This repo includes:

- Notes and insights on MCP & GenAI
- Code implementations via cookbooks
- Links to external resources (Notion pages & courses)

---

## Model Context Protocol (MCP)

### Why MCP?

Understand the motivation and benefits of using MCP:

[**MCP Overview** (Notion)](https://www.notion.so/Why-MCP-2337d374122780daadbaf579ee99c6e5?source=copy_link)

### MCP Architecture

Explore the design and components of MCP:

[**MCP Architecture** (Notion)](https://www.notion.so/MCP-Architecture-2337d374122780728f7af72e9b03f2a8?source=copy_link)


### LLM Chatbot

Hands-on examples using function tool calling with different providers:

- 🤖 **ChatBot using Anthropic**  
  [`tool_calling_anthropic_chatbot.ipynb`](/cookbooks/chatbots/tool_calling_anthropic_chatbot.ipynb)

- 🤖 **ChatBot using OpenAI**  
  [`tool_calling_openai_chatbot.ipynb`](/cookbooks/chatbots/tool_calling_openai_chatbot.ipynb)

### Creating MCP Server

Hands-on guide to creating an MCP server:
- 🖥️ **Creating an MCP Server**  
  [`mcp_server.ipynb`](/cookbooks/mcp_server.ipynb) - This example aligns with exposing the tools via the MCP server.

### Creating MCP Client

Hands-on guide to creating an MCP client:
- 🖥️ **Creating an MCP Client**
  [`mcp_client.ipynb`](/cookbooks/mcp_client.ipynb) - This example aligns with consuming the tools via the MCP client. Additionally, They contains the steps to run the MCP client and interact with the MCP server using LLMs.

### Connecting Reference MCP Servers
Hands-on guide to connecting to reference MCP servers:
- 🔗 **Connecting to Reference MCP Servers**
  [`connect_the_reference_mcp_servers.ipynb`](/cookbooks/connect_the_reference_mcp_servers.ipynb) - This example demonstrates how to connect to various reference MCP servers like `filesystems`, `research_papers`, and `fetch`.

### MCP Resources and Prompts
Hands-on guide to using MCP resources and prompts:
- 📚 **Using MCP Resources and Prompts**
  [`prompts_and_resources_with_mcp.ipynb`](/cookbooks/prompts_and_resources_with_mcp.ipynb) - This example shows how to run the MCP server and client, explore available tools, list and fetch resources, view all prompts, and use prompts with arguments to get results.


**Contributions Welcome!**  
If you’d like to add examples using other providers or open-source models, feel free to open a pull request. I’ll review and merge it.

---

## Learning Resources

I’m learning MCP through a free course by **DeepLearning.AI** and **Anthropic** (creators of MCP):

[**MCP Course – Build Rich Context AI Apps**](https://www.deeplearning.ai/short-courses/mcp-build-rich-context-ai-apps-with-anthropic/)

---

> [!NOTE]
> This repository is a work in progress. More content and examples will be added regularly.

> [!TIP]
> Use the [Notion links & MCP Cookbooks](#model-context-protocol-mcp) above for deep dives and refer to them for practical code.

---

## 🔗 Quick Access

- [MCP Overview (Notion)](https://www.notion.so/Why-MCP-2337d374122780daadbaf579ee99c6e5?source=copy_link)  
- [MCP Architecture (Notion)](https://www.notion.so/MCP-Architecture-2337d374122780728f7af72e9b03f2a8?source=copy_link)  
- [MCP Course - DeepLearning.AI & Anthropic](https://www.deeplearning.ai/short-courses/mcp-build-rich-context-ai-apps-with-anthropic/)  
- [Cookbooks Directory](/cookbooks/)