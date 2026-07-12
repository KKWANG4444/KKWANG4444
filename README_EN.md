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
- 📊 Maintaining an [**AI API Status Monitor**](https://kkwang4444.github.io/api-status/) — tracking the current marketplace catalog across 16+ providers
- 📝 Author of practical guides for developers working with AI APIs in restricted regions
- 🔧 Open source contributor focused on AI accessibility

## 📦 Projects

| Project | Description | Stars |
|:---|:---|:---:|
| [**ai-api-proxy-china-guide**](https://github.com/KKWANG4444/ai-api-proxy-china-guide) | 🇨🇳🇬🇧 Complete guide for AI API access in China — the current marketplace catalog, pitfalls, tool configs | ⭐ |
| [**api-status**](https://github.com/KKWANG4444/api-status) | 📊 Live dashboard monitoring the current marketplace catalog across 16+ providers | ⭐ |
| [**llm-api-proxy-china**](https://github.com/KKWANG4444/llm-api-proxy-china) | 🔌 Full model list & gateway comparison for 16 providers | ⭐ |
| [**stability-tracker**](https://github.com/KKWANG4444/Claude-4.7-GPT-5.5-API-Stability-Tracker) | 📈 public availability and latency observations for flagship AI models | ⭐ |

## 🛠️ What I Build

### AI API Gateway — [aifast.club](https://www.aifast.club)

```
One compatible Base URL → models currently listed in the console
```

| Feature | Description |
|:---|:---|
| **Providers** | OpenAI, Anthropic, xAI, Google, DeepSeek, Alibaba, ByteDance, Zhipu + 8 more |
| **Models** | Claude Sonnet 5, Grok 4.5, Gemini 3.1, DeepSeek V4 + 567 more |
| **Protocol** | 100% OpenAI SDK compatible — drop-in replacement |
| **Access** | Works globally — optimized for China, SE Asia, and restricted regions |

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

## 📊 Live Status

![Status Dashboard](https://kkwang4444.github.io/api-status/assets/img/api-status-screenshot.png)

👉 **[Live Dashboard: Marketplace Model Status](https://kkwang4444.github.io/api-status/)**

> If one of these guides saved you time, star the repository you used. It helps other developers find the useful part instead of another landing page.

## 📫 Connect

- **Website:** [aifast.club](https://www.aifast.club)
- **GitHub:** [@KKWANG4444](https://github.com/KKWANG4444)
- **Gitee:** [@kkwwww4444](https://gitee.com/kkwwww4444)

---

<p align="center">
  <i>Building the bridge between developers and AI — anywhere in the world.</i>
  <br>
  <a href="https://www.aifast.club">🌐 aifast.club</a>
</p>
