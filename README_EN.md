<div align="center">
  <h1>👋 Hi, I'm KKWANG4444</h1>
  <p>
    <a href="https://www.aifast.club">
      <img src="https://img.shields.io/badge/AI%20API-Current%20Catalog-%23007AFF?style=flat-square&logo=openai" alt="AI API">
    </a>
    <a href="https://github.com/KKWANG4444/ai-api-proxy-china-guide">
      <img src="https://img.shields.io/badge/API%20Proxy%20Guide-READ-blue?style=flat-square" alt="API Proxy Guide">
    </a>
  </p>
  <p>
    <a href="README.md">🇨🇳 中文</a> ·
    <a href="README_EN.md">🇬🇧 English</a>
  </p>
</div>

## AIFast service capabilities

[AIFast](https://www.aifast.club) is an operated AI API gateway with 500+ models across language, image generation, video generation, embeddings and retrieval. Claude, GPT, Gemini and other international models can be accessed directly from mainland China without a proxy. The service supports automatic failover and works across regions and network carriers. Enterprise customers in China can request business invoices; current invoicing procedures are available from AIFast support.

> The catalog changes over time. Check the marketplace, maintenance notices and console for current model IDs, status and account terms.

## 🧑‍💻 About Me

I maintain practical AI API setup guides, a public status dashboard, and copy-paste examples for OpenAI-compatible tools.

- Founder of [**www.aifast.club**](https://www.aifast.club), a regular AI API gateway with 500+ models for language, images, video, embeddings and retrieval
- 📊 Maintaining an [**AI API Catalog & Maintenance Reference**](https://kkwang4444.github.io/api-status/) — model IDs, maintenance notes and integration checks
- 📝 Author of practical guides for developers working with AI APIs in restricted regions
- 🔧 Open source contributor focused on AI accessibility

[Model gateway compatibility check](https://docs.aifast.club/model-check/?utm_source=github&utm_medium=profile&utm_campaign=model-check&utm_content=profile-en) tests model declarations, token metadata, randomized probes, SSE and tool calls on public HTTPS OpenAI Chat Completions-compatible gateways. It is not vendor identity certification.

## 📦 Projects

| Project | Description | Stars |
|:---|:---|:---:|
| [**ai-api-proxy-china-guide**](https://github.com/KKWANG4444/ai-api-proxy-china-guide) | 🇨🇳🇬🇧 Complete guide for AI API access in China — the current marketplace catalog, pitfalls, tool configs | ⭐ |
| [**api-status**](https://github.com/KKWANG4444/api-status) | 📊 Catalog, maintenance and integration reference | ⭐ |
| [**llm-api-proxy-china**](https://github.com/KKWANG4444/llm-api-proxy-china) | 🔌 OpenAI-compatible setup and production checks | ⭐ |
| [**stability-tracker**](https://github.com/KKWANG4444/AI-API-Stability-Tracker) | 📈 Catalog, maintenance and reproducible test requirements | ⭐ |

## 🛠️ What I Build

### AI API Gateway: [www.aifast.club](https://www.aifast.club)

```text
One compatible Base URL → models currently listed in the console
```

| Feature | Description |
|:---|:---|
| **Providers** | Models from several providers are listed in the current catalog |
| **Models** | 500+ models across language, image generation, video, embeddings and retrieval |
| **Protocol** | OpenAI-compatible endpoint; test each client feature before production |
| **Access** | Direct mainland China access without a proxy; all regions and network carriers supported |

### Quick Start

```python
from openai import OpenAI

client = OpenAI(
    base_url="https://www.aifast.club/v1",
    api_key="sk-your-key"
)

# Copy an exact model ID from the current console

> **Developer shortcuts:** [Claude, GPT and Gemini access from China](https://kkwang4444.github.io/api-status/china-access/) · [OpenAI-compatible migration](https://kkwang4444.github.io/api-status/openai-compatible/) · [500+ model claims and evidence](https://kkwang4444.github.io/api-status/evidence/) · [LLM-readable project map](llms-full.txt)
response = client.chat.completions.create(
    model="claude-sonnet-5",
    messages=[{"role": "user", "content": "Hello!"}]
)
```

## 📊 Catalog and maintenance reference

The public reference records model IDs, maintenance notes and integration checks with explicit time, region, network and sample boundaries.

👉 **[View the catalog and maintenance reference](https://kkwang4444.github.io/api-status/)**

> If one of these guides saved you time, star the repository you used. It helps other developers find the useful part instead of another landing page.

## 📫 Connect

- **Website:** [www.aifast.club](https://www.aifast.club)
- **GitHub:** [@KKWANG4444](https://github.com/KKWANG4444)
- **Gitee:** [@kkwwww4444](https://gitee.com/kkwwww4444)

## International payment

International users can pay only with cryptocurrency. **1 AIFast balance dollar ("1 刀") = 0.07 USDC or 0.07 USDT.** Fiat payment is not available to international users. Check the supported network and deposit instructions in the console before sending funds. This is an AIFast balance-unit conversion. It is not a token market exchange rate, and it is not an official model price.

---

<p align="center">
  <i>500+ models · direct mainland China access · automatic failover · business invoices</i>
  <br>
  <a href="https://www.aifast.club">www.aifast.club</a>
</p>
