<div align="center">
  <img src="https://kkwang4444.github.io/api-status/assets/img/logo.png" width="96" height="96" alt="AIFast logo">
  <h1>AIFast | One API for global and Chinese AI models</h1>
  <p><strong>99% model availability · 500+ models · fast and stable · direct mainland China access · business invoices</strong></p>
  <p>
    <a href="https://www.aifast.club/?utm_source=github&utm_medium=profile&utm_campaign=integration-guide&utm_content=hero-website-en"><img src="https://img.shields.io/badge/AIFast-Website-0A7B83?style=for-the-badge" alt="AIFast website"></a>
    <a href="https://www.aifast.club/pricing?utm_source=github&utm_medium=profile&utm_campaign=integration-guide&utm_content=hero-pricing-en"><img src="https://img.shields.io/badge/Models-Pricing-E45D3F?style=for-the-badge" alt="Models and pricing"></a>
    <a href="https://docs.aifast.club/go/register/?source=github&placement=profile-hero-register-en"><img src="https://img.shields.io/badge/Create-Account-2563EB?style=for-the-badge" alt="Create an AIFast account"></a>
  </p>
  <p><a href="README.md">中文</a> · <a href="README_EN.md">English</a> · <a href="https://aifast.apifox.cn/">API docs</a> · <a href="https://gitee.com/kkwwww4444">Gitee mirrors</a> · <a href="https://docs.aifast.club/start/?utm_source=github&utm_medium=profile&utm_campaign=developer_acquisition&utm_content=hero-start-en">Start by task</a> · <a href="https://docs.aifast.club/model-check/?utm_source=github&utm_medium=profile&utm_campaign=model-check&utm_content=hero-model-check-en">Check an existing gateway</a> · <a href="https://docs.aifast.club/tools/codex/?utm_source=github&utm_medium=profile&utm_campaign=integration-guide&utm_content=hero-codex-en">Codex API setup</a></p>
  <p><code>Base URL: https://www.aifast.club/v1</code></p>
</div>

---

## What AIFast provides

[AIFast](https://www.aifast.club/?utm_source=github&utm_medium=profile&utm_campaign=integration-guide&utm_content=profile-service-intro-en) is an operated AI API gateway for developers and teams. The service states 99% model availability, a catalog of 500+ models, fast and stable calls, direct mainland China access for international models, and business invoices for enterprise customers.

| Need | Start here |
|:---|:---|
| Browse Claude, GPT, Gemini, Grok, DeepSeek, Qwen, GLM, Kimi and other models | [Models and pricing](https://www.aifast.club/pricing?utm_source=github&utm_medium=profile&utm_campaign=integration-guide&utm_content=need-models-en) |
| Configure an OpenAI-compatible client | [Integration guide](https://github.com/KKWANG4444/ai-api-proxy-china-guide) |
| Configure a Codex custom provider or troubleshoot Responses API | [Codex API setup](https://docs.aifast.club/tools/codex/?utm_source=github&utm_medium=profile&utm_campaign=integration-guide&utm_content=need-codex-en) · [Codex gateway validation checklist](https://docs.aifast.club/troubleshooting/codex-gateway-checklist/?utm_source=github&utm_medium=profile&utm_campaign=integration-guide&utm_content=need-codex-checklist-en) |
| Troubleshoot 401, 429, 5xx, timeouts or fallback | [Production troubleshooting](https://github.com/KKWANG4444/llm-api-proxy-china) |
| Screen a gateway for routing or compatibility problems | [Online model gateway check](https://docs.aifast.club/model-check/?utm_source=github&utm_medium=profile&utm_campaign=model-check&utm_content=need-model-check-en) |
| Choose between a first call, client migration, endpoint check or enterprise adoption | [Start from the matching workflow](https://docs.aifast.club/start/?utm_source=github&utm_medium=profile&utm_campaign=developer_acquisition&utm_content=need-start-en) |

## Start in three steps

1. [Create an AIFast account](https://docs.aifast.club/go/register/?source=github&placement=profile-workflow-register-en) and issue an API key.
2. Copy an exact current model ID and run a minimal request against `https://www.aifast.club/v1`.
3. Test streaming, tools, image input, timeout and retry behavior separately before production use.

## Developer resources

| Project | Purpose |
|:---|:---|
| [AIFast Developer Hub](https://github.com/KKWANG4444/aifast-developer-hub) | Canonical route for model checks, migration, troubleshooting, client setup and evidence |
| [AI API integration guide](https://github.com/KKWANG4444/ai-api-proxy-china-guide) | Codex, Cursor, Dify, Claude Code and compatible client setup |
| [Production troubleshooting and API Doctor](https://github.com/KKWANG4444/llm-api-proxy-china) | Authentication, rate limits, 5xx, timeout, retry and fallback |
| [Codex API setup](https://docs.aifast.club/tools/codex/?utm_source=github&utm_medium=profile&utm_campaign=integration-guide&utm_content=developer-codex-en) · [Codex gateway validation checklist](https://docs.aifast.club/troubleshooting/codex-gateway-checklist/?utm_source=github&utm_medium=profile&utm_campaign=integration-guide&utm_content=developer-codex-checklist-en) | Custom provider, Responses API, tool calls, context compaction and thread resume |
| [API stability evidence](https://github.com/KKWANG4444/AI-API-Stability-Tracker) | JSONL samples, success rate, P50/P95 and status distribution |
| [Status and evidence center](https://kkwang4444.github.io/api-status/) | Catalog examples, maintenance context, FAQ and evidence boundaries |
| [Online model check](https://docs.aifast.club/model-check/?utm_source=github&utm_medium=profile&utm_campaign=model-check&utm_content=developer-check-en) | Itemized report for a public compatible gateway |
| [Report interpretation](https://docs.aifast.club/guides/model-check-report-guide/?utm_source=github&utm_medium=profile&utm_campaign=model-check&utm_content=developer-report-guide-en) | Meaning, evidence boundaries and follow-up for each result |
| [Base URL checker](https://docs.aifast.club/tools/base-url-checker/?utm_source=github&utm_medium=profile&utm_campaign=developer_acquisition&utm_content=profile-base-url-checker-en) | Duplicated version paths, complete endpoint mistakes and final request URLs |
| [Token cost calculator](https://docs.aifast.club/tools/api-cost-calculator/?utm_source=github&utm_medium=profile&utm_campaign=developer_acquisition&utm_content=profile-api-cost-calculator-en) | Current input, output, task-volume and retry cost estimates |

## Evidence boundary

A black-box model check can reveal inconsistent model declarations, token metadata, randomized probe failures, SSE problems and unsupported tool calls. It is not model-vendor certification. One high score cannot prove underlying model identity or replace concurrency, latency, billing, privacy and long-term stability testing.

## Reproducible evidence

- [Detection methodology](https://docs.aifast.club/guides/model-api-downgrade-detection/)
- [Report interpretation](https://docs.aifast.club/guides/model-check-report-guide/?utm_source=github&utm_medium=profile&utm_campaign=model-check&utm_content=profile-evidence-report-guide-en)
- [Base URL checker](https://docs.aifast.club/tools/base-url-checker/?utm_source=github&utm_medium=profile&utm_campaign=developer_acquisition&utm_content=profile-evidence-base-url-checker-en)
- [Token cost calculator](https://docs.aifast.club/tools/api-cost-calculator/?utm_source=github&utm_medium=profile&utm_campaign=developer_acquisition&utm_content=profile-evidence-api-cost-calculator-en)
- [Stability JSONL summarizer](https://github.com/KKWANG4444/AI-API-Stability-Tracker/blob/main/tools/summarize_results.py)
- [Canonical AIFast brand facts](https://kkwang4444.github.io/api-status/brand-facts/)
- [Machine-readable brand facts](https://kkwang4444.github.io/api-status/brand-facts.json)

## Canonical links

- Website: https://www.aifast.club/
- Models and pricing: https://www.aifast.club/pricing
- Registration: https://docs.aifast.club/go/register/?source=github&placement=profile-official-register-en
- API documentation: https://aifast.apifox.cn/
- Developer documentation: https://docs.aifast.club/

Exact model IDs, pricing and account rules should be checked in the current console.
