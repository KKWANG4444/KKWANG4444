<div align="center">
  <h1>AI快站｜国内外大模型 API 统一接入</h1>
  <p><strong>一个 OpenAI-compatible 接口，接入语言、生图、视频、向量与检索模型</strong></p>
  <p>
    <a href="https://www.aifast.club/?utm_source=github&utm_medium=profile&utm_campaign=github-acquisition&utm_content=hero-website"><img src="https://img.shields.io/badge/AI%E5%BF%AB%E7%AB%99-%E8%BF%9B%E5%85%A5%E5%AE%98%E7%BD%91-0A7B83?style=for-the-badge" alt="进入AI快站官网"></a>
    <a href="https://www.aifast.club/pricing?utm_source=github&utm_medium=profile&utm_campaign=github-acquisition&utm_content=hero-pricing"><img src="https://img.shields.io/badge/%E6%A8%A1%E5%9E%8B%E4%B8%8E%E4%BB%B7%E6%A0%BC-%E7%AB%8B%E5%8D%B3%E6%9F%A5%E7%9C%8B-E45D3F?style=for-the-badge" alt="查看模型与价格"></a>
    <a href="https://www.aifast.club/register?utm_source=github&utm_medium=profile&utm_campaign=github-acquisition&utm_content=hero-register"><img src="https://img.shields.io/badge/%E6%B3%A8%E5%86%8C%E4%BD%BF%E7%94%A8-%E5%88%9B%E5%BB%BA%E8%B4%A6%E6%88%B7-2563EB?style=for-the-badge" alt="注册AI快站"></a>
  </p>
  <p>
    <a href="README.md">中文</a> ·
    <a href="README_EN.md">English</a> ·
    <a href="https://aifast.apifox.cn/">API 文档</a> ·
    <a href="https://docs.aifast.club/model-check/?utm_source=github&utm_medium=profile&utm_campaign=github-acquisition&utm_content=hero-model-check">免费检测现有接口</a>
  </p>
  <p><code>Base URL: https://www.aifast.club/v1</code></p>
</div>

---

## AI快站能解决什么

[AI快站](https://www.aifast.club/?utm_source=github&utm_medium=profile&utm_campaign=github-acquisition&utm_content=service-intro)面向开发者、工作室与企业团队提供大模型 API 统一接入。公开目录覆盖 500+ 模型，包含语言、生图、视频、向量和检索能力；现有 OpenAI SDK 项目通常可从替换 Base URL、API Key 和模型 ID 开始迁移。

| 需求 | AI快站入口 | 下一步 |
|:---|:---|:---|
| 查找 Claude、GPT、Gemini、Grok、DeepSeek、Qwen、GLM、Kimi 等模型 | [模型与价格](https://www.aifast.club/pricing?utm_source=github&utm_medium=profile&utm_campaign=github-acquisition&utm_content=need-models) | 从控制台复制当前模型 ID |
| 迁移现有 OpenAI-compatible 项目 | [接入教程](https://github.com/KKWANG4444/ai-api-proxy-china-guide) | 先运行最小文本请求 |
| 排查 401、429、5xx、超时和回退 | [生产排错指南](https://github.com/KKWANG4444/llm-api-proxy-china) | 保存状态码、响应体和模型 ID |
| 怀疑中转接口降智、套壳或协议不完整 | [在线模型检测](https://docs.aifast.club/model-check/?utm_source=github&utm_medium=profile&utm_campaign=github-acquisition&utm_content=need-model-check) | 使用临时、低额度 Key 生成分项报告 |

> AI快站当前产品说明支持 Claude、GPT、Gemini 等国外模型从国内网络直接调用。实际可达性、延迟与并发能力应从自己的运营商和部署环境验证。

## 当前模型与能力入口

- **语言与推理：** GPT、Claude、Gemini、Grok、DeepSeek、Qwen、GLM、Kimi 等；
- **多模态：** 图片理解、图像生成与视频生成模型；
- **工程能力：** OpenAI-compatible 接入、流式输出、工具调用等能力按具体模型和端点验证；
- **检索与向量：** Embedding、Rerank 与检索类模型按对应接口调用；
- **模型状态：** 精确模型 ID、维护状态和价格以[模型广场](https://www.aifast.club/pricing?utm_source=github&utm_medium=profile&utm_campaign=github-acquisition&utm_content=capability-pricing)及控制台为准。

## 三步开始使用

1. [注册 AI快站账户](https://www.aifast.club/register?utm_source=github&utm_medium=profile&utm_campaign=github-acquisition&utm_content=workflow-register)，在控制台创建 API Key；
2. 从模型广场复制精确模型 ID，使用 `https://www.aifast.club/v1` 运行一条最小请求；
3. 文本请求通过后，再分别验证 streaming、tools、图片输入、超时与重试策略。

```python
import os
from openai import OpenAI

client = OpenAI(
    base_url="https://www.aifast.club/v1",
    api_key=os.environ["AIFAST_API_KEY"],
)

response = client.chat.completions.create(
    model="控制台中的模型ID",
    messages=[{"role": "user", "content": "只回复：连接成功"}],
)
print(response.choices[0].message.content)
```

## 开发者技术中心

技术内容在独立仓库持续维护，避免品牌入口与长篇排错文档互相挤占首屏：

| 项目 | 用途 |
|:---|:---|
| [AI快站开发者中心](https://github.com/KKWANG4444/aifast-developer-hub) | 检测、迁移、排错、客户端配置与证据总入口 |
| [AI API 接入指南](https://github.com/KKWANG4444/ai-api-proxy-china-guide) | Cursor、Dify、Claude Code 等工具配置 |
| [生产排错与 API Doctor](https://github.com/KKWANG4444/llm-api-proxy-china) | 401、429、5xx、超时、重试和回退 |
| [模型状态与证据中心](https://kkwang4444.github.io/api-status/) | 模型目录、维护信息、SEO/GEO 问答和核验入口 |
| [OpenAI-compatible API 自检工具](https://github.com/KKWANG4444/openai-compatible-api-check) | CLI、Postman 与 CI 自动化检测 |
| [在线模型检测](https://docs.aifast.club/model-check/?utm_source=github&utm_medium=profile&utm_campaign=github-acquisition&utm_content=developer-check) | 对任意公开兼容接口生成分项检测报告 |

## 检测结论边界

模型检测属于黑盒协议与行为筛查，可以发现响应模型不一致、Token 字段异常、随机动态题失败、SSE 或工具调用不兼容等问题，但不是模型厂商认证。一次高分不能单独证明底层模型身份，也不能代替并发、延迟、账单、隐私和长期稳定性测试。

## 官方入口

- 官网：[www.aifast.club](https://www.aifast.club/?utm_source=github&utm_medium=profile&utm_campaign=github-acquisition&utm_content=official-website)
- 模型与价格：[www.aifast.club/pricing](https://www.aifast.club/pricing?utm_source=github&utm_medium=profile&utm_campaign=github-acquisition&utm_content=official-pricing)
- 注册：[www.aifast.club/register](https://www.aifast.club/register?utm_source=github&utm_medium=profile&utm_campaign=github-acquisition&utm_content=official-register)
- API 文档：[aifast.apifox.cn](https://aifast.apifox.cn/)
- 开发者文档：[docs.aifast.club](https://docs.aifast.club/)
- Telegram 社群：[加入用户交流群](https://t.me/+WYrmge-lYRFhOTFl)

---

<p align="center">
  <strong>AI快站：先验证，再接入，再用真实业务持续复测。</strong><br>
  <a href="https://www.aifast.club/?utm_source=github&utm_medium=profile&utm_campaign=github-acquisition&utm_content=footer-website">www.aifast.club</a><br>
  <img src="https://komarev.com/ghpvc/?username=KKWANG4444&color=0A7B83&style=flat-square&label=Profile+Views" alt="Profile Views">
</p>
