# Awesome AI API Relay & Gateway (2026)

![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square)
![Last Updated](https://img.shields.io/badge/updated-2026--11-blue?style=flat-square)

**[中文](README.md) | English**

> A curated, continuously maintained index of AI API relay services, aggregators, official platforms, coding-CLI providers, and self-hosted gateways.
>
> **This is an information index, not a commercial recommendation.** Verify pricing, KYC, terms, and reliability before using any service.

**Last updated: 2026-11-17**

---

## Contents

1. [How to choose a relay](#1-how-to-choose-a-relay)
2. [General relay services (multi-model)](#2-general-relay-services-multi-model)
3. [Chinese open-model / quasi-official platforms](#3-chinese-open-model--quasi-official-platforms)
4. [International official platforms](#4-international-official-platforms)
5. [International aggregators / inference platforms](#5-international-aggregators--inference-platforms)
6. [Claude Code / Cursor / Codex CLI providers](#6-claude-code--cursor--codex-cli-providers)
7. [Self-hosted gateways](#7-self-hosted-gateways)
8. [Quick selection guide](#8-quick-selection-guide)
9. [Safety checklist](#9-safety-checklist)
10. [Pricing basics](#10-pricing-basics)
11. [FAQ](#11-faq)
12. [Contributing](#12-contributing)

---

## 1. How to choose a relay

| # | Check | Why it matters |
|---|---|---|
| 1 | **Reliability** | Uptime, peak-hour behavior, status page/announcements |
| 2 | **Model coverage & freshness** | New models added quickly; OpenAI/Anthropic/Gemini native protocols |
| 3 | **Transparent pricing** | Public price tables, cache pricing, top-up exchange rate, itemized billing |
| 4 | **Payment options** | Alipay, WeChat Pay, USDT, cards; low minimum top-up |
| 5 | **Company & support** | Registered entity, invoices, responsive support |
| 6 | **Data & compliance** | Request logging policy, enterprise compliance features |
| 7 | **Exit risk** | Avoid large balances on new/small services; test small first |

> Rule of thumb: **test small → validate real workloads → only then commit larger balance.**

---

## 2. General relay services (multi-model)

| Service | Link | Notes |
|---|---|---|
| PoloAPI | https://poloai.top | Claude Code / CodeX support; balanced |
| Weelinking | https://www.weelinking.com | Multi-route redundancy; ~¥0.8 per $1 |
| **BullRoute** | https://bullroute.com | OpenAI / Anthropic / Gemini compatible, 50+ models, pay-per-token, USDT auto top-up & Alipay; public [pricing](https://bullroute.com/pricing/) and [docs](https://bullroute.com/docs/) |
| n1n.ai | https://n1n.ai | Low latency; beginner friendly |
| Lingya API | https://api.lingyaai.cn | China direct line; invoices |
| Quanzil | https://quanzil.com | Full-model support; China direct |
| OfoxAI | https://ofox.ai | Native Anthropic format; Claude Code integration |
| 302.AI | https://302.ai | 500+ models; pay-as-you-go |
| Yunwu API | https://yunwu.ai | 500+ models; ~¥0.5 per $1 |
| UIUIAPI | https://uiuiapi.com | 300+ models; enterprise concurrency; invoices |
| CloseAI | https://www.closeai-asia.com | Enterprise-grade official routing |
| TokenMix | https://tokenmix.ai | Alipay/WeChat/Stripe; OpenAI compatible |
| B.AI | https://b.ai | Multi-model; USDT payments |
| Laozhang AI | https://laozhang.ai | Popular Chinese Claude relay |
| DMXAPI | https://dmxapi.com | 480+ models; three native protocols |
| API易 | https://apiyi.com | Lightweight; low cache pricing |
| NoneLinear | https://nonelinear.com | 480+ models; three protocols; SLA |
| 88API | https://88api.ai | Broad catalog; fast new-model updates |
| ToTokens | https://totokens.cc | GPT/Claude/Grok/Gemini; failover groups |
| Yundu | https://yundu.lol | GPT/Claude groups |
| Jiekou AI | https://jiekou.ai | Personal & enterprise |
| NodAPI | https://nodapi.com | Multi-model; low latency |
| OAIPro | https://api.oaipro.com | Official routing; near-official pricing |

---

## 3. Chinese open-model / quasi-official platforms

| Platform | Link | Notes |
|---|---|---|
| SiliconFlow | https://cloud.siliconflow.cn | Open models; free credits (global: https://www.siliconflow.com) |
| ModelScope | https://www.modelscope.cn | Alibaba ecosystem; shared free quota |
| Alibaba Bailian | https://bailian.aliyun.com | Enterprise-grade |
| Tencent Hunyuan | https://hunyuan.tencent.com | Hunyuan series |
| Huawei Pangu | https://pangu.huaweicloud.com | Enterprise & compliance |
| Zhipu BigModel | https://bigmodel.cn | GLM series |
| iFlytek Spark | https://xinghuo.xfyun.cn | Speech & text |
| DeepSeek | https://platform.deepseek.com | Official DeepSeek API |
| Moonshot Kimi | https://platform.moonshot.cn | Kimi series |
| Volcengine Ark | https://www.volcengine.com/product/ark | ByteDance ecosystem |
| MiniMax | https://www.minimaxi.com | Multimodal |
| StepFun | https://platform.stepfun.com | Step series |
| Baichuan | https://platform.baichuan-ai.com | Baichuan series |

---

## 4. International official platforms

| Platform | Link | Notes |
|---|---|---|
| OpenAI | https://platform.openai.com | GPT models |
| Anthropic | https://console.anthropic.com | Claude models |
| Google Gemini | https://ai.google.dev | Gemini models |
| Azure OpenAI | https://azure.microsoft.com/en-us/products/ai-services/openai-service | Microsoft-hosted OpenAI |
| AWS Bedrock | https://aws.amazon.com/bedrock/ | Multi-model hosting |
| Google Vertex AI | https://cloud.google.com/vertex-ai | GCP multi-model |
| Mistral | https://console.mistral.ai | Official Mistral |
| Cohere | https://dashboard.cohere.com | Official Cohere |
| xAI | https://console.x.ai | Grok models |

---

## 5. International aggregators / inference platforms

| Platform | Link | Notes |
|---|---|---|
| OpenRouter | https://openrouter.ai | Large multi-model marketplace |
| Together AI | https://api.together.xyz | Open-model inference, low cost |
| Groq | https://console.groq.com | LPU inference, very low latency, free tier |
| Fireworks AI | https://fireworks.ai | Enterprise inference |
| DeepInfra | https://deepinfra.com | Pay-per-use, low latency |
| Replicate | https://replicate.com | Model hosting |
| Poe API | https://poe.com/api | Quora's multi-model API |
| Perplexity API | https://docs.perplexity.ai | Search-augmented models |

---

## 6. Claude Code / Cursor / Codex CLI providers

| Service | Link | Notes |
|---|---|---|
| packyapi | https://www.packyapi.com | Claude Code / Gemini CLI |
| OfoxAI | https://ofox.ai | Native Anthropic protocol |
| Code By AI | https://www.codebyai.net | One key for Claude Code / Codex / Gemini CLI |
| lanbuff | https://lanbuff.app | Claude Code / Codex groups; invoices |
| CloseAI | https://www.closeai-asia.com | Claude Code / CodeX support |

> CLI tools usually only need `ANTHROPIC_BASE_URL` and `ANTHROPIC_AUTH_TOKEN`; see each provider's docs.

---

## 7. Self-hosted gateways

| Project | Link | Notes |
|---|---|---|
| new-api | https://github.com/Calcium-Ion/new-api | Popular open-source AI gateway |
| one-api | https://github.com/songquanpeng/one-api | Mature open-source gateway |
| LiteLLM | https://github.com/BerriAI/litellm | Python gateway, 100+ models |
| Portkey Gateway | https://github.com/Portkey-AI/gateway | Production AI gateway |
| Higress | https://github.com/alibaba/higress | Cloud-native AI gateway |
| Bifrost | https://github.com/maximhq/bifrost | High-performance LLM gateway |

---

## 8. Quick selection guide

| Scenario | Recommendation | Why |
|---|---|---|
| Personal testing | Relay with low minimum top-up | Cheap comparison |
| Coding (Cursor / Claude Code) | Native Anthropic/OpenAI protocol | Tool-call reliability |
| Enterprise production | Entity + invoices + SLA | Compliance & stability |
| Chinese models | Official Chinese platforms | Speed & compliance |
| Global payments | USDT/card-supporting relays or official APIs | Convenience |
| Sensitive data | Self-hosted gateway + official keys | Data control |

---

## 9. Safety checklist

1. Never load large balances onto new or small services — test small first.
2. Be skeptical of prices far below official cost.
3. Check cache read/write pricing before committing.
4. Confirm the top-up exchange rate (`$1 credit = how much CNY`).
5. Keep itemized billing records.
6. Never expose API tokens in frontend code.
7. Check whether the provider logs prompts/completions.
8. Confirm invoicing/contract options for business purchases.

---

## 10. Pricing basics

- **Per token**: input and output are usually priced separately, typically USD per 1M tokens.
- **Per call**: image, video, and audio models are often billed per request.
- **Rate multipliers**: some relays price as "multiplier × official price"; check the baseline.
- **Top-up rate**: `$1 credit = ¥X` varies significantly between services.
- **Prompt caching**: cached input is often 10%–25% of normal price; confirm with the provider.
- **Minimum top-up**: many services allow $1–$10 to start.

---

## 11. FAQ

**How is a relay different from official APIs?**
Official APIs are the most stable and transparent but may require overseas payment/network. Relays offer a unified endpoint and local payments, at the cost of extra reliability/compliance due diligence.

**Can one Base URL call all models?**
Most relays are OpenAI-compatible; some also expose Anthropic/Gemini native protocols. Check each provider's docs.

**Is USDT top-up safe?**
Choose providers with automatic crediting and clear rules; verify credited amounts and network fees.

**Does this repo charge for listings?**
No. Listings are for information only and are not endorsements.

---

## 12. Contributing

PRs are welcome — see [CONTRIBUTING.md](CONTRIBUTING.md). Format:

```markdown
| Service | https://example.com | One-line description (protocol/models/payment/min top-up) |
```

Rules: links must work; descriptions must be factual; affiliate-only spam is rejected; note any referral relationship.

## Changelog

- **2026-11-17** — Repository created; initial categories and safety guide.
