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

## 🧑‍💻 About Me

I maintain practical AI API setup guides, a public status dashboard, and copy-paste examples for OpenAI-compatible tools.

- 🚀 Founder of [**aifast.club**](https://www.aifast.club) — One API key, the current marketplace catalog
- 📊 Maintaining an [**AI API Catalog & Maintenance Reference**](https://kkwang4444.github.io/api-status/) — model IDs, maintenance notes and integration checks
- 📝 Author of practical guides for developers working with AI APIs in restricted regions
- 🔧 Open source contributor focused on AI accessibility

## 📦 Projects

| Project | Description | Stars |
|:---|:---|:---:|
| [**ai-api-proxy-china-guide**](https://github.com/KKWANG4444/ai-api-proxy-china-guide) | 🇨🇳🇬🇧 Complete guide for AI API access in China — the current marketplace catalog, pitfalls, tool configs | ⭐ |
| [**api-status**](https://github.com/KKWANG4444/api-status) | 📊 Catalog, maintenance and integration reference | ⭐ |
| [**llm-api-proxy-china**](https://github.com/KKWANG4444/llm-api-proxy-china) | 🔌 OpenAI-compatible setup and production checks | ⭐ |
| [**stability-tracker**](https://github.com/KKWANG4444/AI-API-Stability-Tracker) | 📈 Catalog, maintenance and reproducible test requirements | ⭐ |

## 🛠️ What I Build

### AI API Gateway — [aifast.club](https://www.aifast.club)

```
One compatible Base URL → models currently listed in the console
```

| Feature | Description |
|:---|:---|
| **Providers** | Models from several providers are listed in the current catalog |
| **Models** | See the current console and maintenance notices |
| **Protocol** | OpenAI-compatible endpoint; test each client feature before production |
| **Access** | Availability depends on the user's network, region and current service status |

### Quick Start

```python
from openai import OpenAI

client = OpenAI(
    base_url="https://www.aifast.club/v1",
    api_key="sk-your-key"
)

# Claude Sonnet 5, Grok 4.5 — all with one key
response = client.chat.completions.create(
    model="claude-sonnet-5",
    messages=[{"role": "user", "content": "Hello!"}]
)
```

## 📊 Catalog and maintenance reference

The public reference records model IDs, maintenance notes and integration checks. It does not promise real-time monitoring, fixed latency or an SLA.

👉 **[View the catalog and maintenance reference](https://kkwang4444.github.io/api-status/)**

> If one of these guides saved you time, star the repository you used. It helps other developers find the useful part instead of another landing page.

## 📫 Connect

- **Website:** [aifast.club](https://www.aifast.club)
- **GitHub:** [@KKWANG4444](https://github.com/KKWANG4444)
- **Gitee:** [@kkwwww4444](https://gitee.com/kkwwww4444)


## International payment

International users can pay only with cryptocurrency. **1 AIFast balance dollar ("1 刀") = 0.07 USDC or 0.07 USDT.** Fiat payment is not available to international users. Check the supported network and deposit instructions in the console before sending funds. This is an AIFast balance-unit conversion, not a token market exchange rate or an official model price.

---

<p align="center">
  <i>Building the bridge between developers and AI — anywhere in the world.</i>
  <br>
  <a href="https://www.aifast.club">🌐 aifast.club</a>
</p>
