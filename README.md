# Awesome AI API Relay & Gateway 中转站合集（2026）

![GitHub stars](https://img.shields.io/github/stars/Leo-sail/bullrouteAPI?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/Leo-sail/bullrouteAPI?style=flat-square)
![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square)
![Last Updated](https://img.shields.io/badge/updated-2026--11-blue?style=flat-square)

**中文 | [English](README.en.md)**

> 一份持续维护的 AI API 中转站 / 聚合网关 / 官方平台索引，覆盖国际模型综合站、国内开源模型平台、国际官方与聚合平台、Claude Code / Cursor 专用站，以及开源自建方案。
>
> **本文档仅做信息整理，不构成商业推荐。** 使用任何平台前请自行核实资质、价格与条款；建议小额测试后再投入生产。

**最后更新：2026-11-17**

---

## 目录

1. [如何挑选一个靠谱的中转站](#一如何挑选一个靠谱的中转站)
2. [综合中转站（国际模型全支持）](#二综合中转站国际模型全支持)
3. [国内开源模型平台 / 准官方平台](#三国内开源模型平台--准官方平台)
4. [国际官方平台](#四国际官方平台)
5. [国际聚合 / 推理平台](#五国际聚合--推理平台)
6. [Claude Code / Cursor / Codex CLI 专用站](#六claude-code--cursor--codex-cli-专用站)
7. [开源自建方案（自己搭网关）](#七开源自建方案自己搭网关)
8. [选型速查表](#八选型速查表)
9. [安全避坑指南](#九安全避坑指南)
10. [价格与计费科普](#十价格与计费科普)
11. [FAQ](#十一faq)
12. [贡献指南](#十二贡献指南)

---

## 一、如何挑选一个靠谱的中转站

中转站（又称 API 中转、API 代理、API 聚合）解决的是「一个 Base URL 调用多家模型」的问题。挑站时建议按以下顺序检查：

| # | 检查项 | 说明 |
|---|---|---|
| 1 | **稳定性** | 是否经常宕机、高峰期是否可用、有无状态页/公告群 |
| 2 | **模型覆盖与上新速度** | 是否及时跟进官方新模型，是否支持 OpenAI / Anthropic / Gemini 原生协议 |
| 3 | **计费透明度** | 是否公开模型价格、倍率、缓存价、充值汇率；账单是否可查 |
| 4 | **支付方式** | 支付宝/微信/USDT/银行卡；是否支持小额起充 |
| 5 | **资质与售后** | 是否有公司主体、能否开票、客服响应速度 |
| 6 | **数据与合规** | 是否记录/留存请求内容，是否支持企业合规需求 |
| 7 | **跑路风险** | 新站不建议大额充值；优先选择运营时间较长、有用户群的站 |

> 经验法则：**先小额测试 → 跑通真实场景 → 再决定是否充值大额。**

---

## 二、综合中转站（国际模型全支持）

> 特点：一个 Base URL 调用 GPT / Claude / Gemini / Grok / DeepSeek 等主流模型，通常兼容 OpenAI SDK。

| 站点 | 链接 | 特点 |
|---|---|---|
| PoloAPI | https://poloai.top | 支持 Claude Code / CodeX，均衡型 |
| Weelinking | https://www.weelinking.com | 多线路冗余，充值汇率约 0.8 元/美元 |
| BullRoute | https://bullroute.com | OpenAI / Anthropic / Gemini 系列模型，按量计费，支持 USDT 与支付宝 |
| n1n.ai | https://n1n.ai | 低延迟，新手友好 |
| 灵芽API | https://api.lingyaai.cn | 国内专线，可开票 |
| Quanzil | https://quanzil.com | 国内直连，全模型支持 |
| OfoxAI | https://ofox.ai | 原生 Anthropic 格式，Claude Code / OpenClaw 集成 |
| 302.AI | https://302.ai | 500+ 模型聚合，按量付费 |
| 云雾API | https://yunwu.ai | 500+ 模型，充值汇率约 0.5 元/美元 |
| UIUIAPI | https://uiuiapi.com | 300+ 模型，企业高并发，可开票 |
| CloseAI | https://www.closeai-asia.com | 企业级，官转为主 |
| TokenMix | https://tokenmix.ai | 支付宝 / 微信 / Stripe，OpenAI 兼容 |
| B.AI | https://b.ai | 全系列模型，USDT 支付 |
| 老板AI | https://laozhang.ai | 中文 Claude 中转，官方同价 |
| DMXAPI | https://dmxapi.com | 480+ 模型，三大原生协议 |
| API易 | https://apiyi.com | 轻量极简，缓存读写低价 |
| NoneLinear | https://nonelinear.com | 480+ 模型，三协议，SLA 宣称 99.99% |
| 88API | https://88api.ai | 模型齐全，上新快 |
| ToTokens | https://totokens.cc | GPT / Claude / Grok / Gemini，分组容灾 |
| 云渡 | https://yundu.lol | GPT / Claude 分组丰富 |
| 接口AI | https://jiekou.ai | 个人 / 企业通用 |
| NodAPI | https://nodapi.com | 多模型聚合，低延迟高并发 |
| OAIPro | https://api.oaipro.com | 官转，价格接近官方 |

> 说明：以上部分信息整理自公开资料与社区反馈，价格与可用性可能随时变化，请以各站实际页面为准。

---

## 三、国内开源模型平台 / 准官方平台

> 适合：需要 DeepSeek / Qwen / GLM / Kimi / 混元等国内模型，或需要国内合规、发票、专线加速的场景。

| 平台 | 链接 | 说明 |
|---|---|---|
| 硅基流动 SiliconFlow | https://cloud.siliconflow.cn | 开源模型聚合，注册送额度（国际版：https://www.siliconflow.com） |
| 魔搭 ModelScope | https://www.modelscope.cn | 阿里系模型社区，共享免费额度 |
| 阿里云百炼 | https://bailian.aliyun.com | 阿里云生态，企业级 |
| 腾讯云混元 | https://hunyuan.tencent.com | 腾讯混元系列 |
| 华为云盘古 | https://pangu.huaweicloud.com | 企业级、合规 |
| 智谱 BigModel | https://bigmodel.cn | GLM 系列，中文优化 |
| 讯飞星火 | https://xinghuo.xfyun.cn | 语音 / 文本 |
| DeepSeek 官方 | https://platform.deepseek.com | DeepSeek 官方 API，价格低 |
| 月之暗面 Kimi | https://platform.moonshot.cn | Kimi 系列 |
| 火山方舟 | https://www.volcengine.com/product/ark | 字节跳动生态，多模型 |
| MiniMax | https://www.minimaxi.com | 多模态模型 |
| 阶跃星辰 | https://platform.stepfun.com | Step 系列模型 |
| 百川智能 | https://platform.baichuan-ai.com | Baichuan 系列 |

---

## 四、国际官方平台

> 最稳定、价格最透明，但可能需要海外支付方式与网络环境。

| 平台 | 链接 | 说明 |
|---|---|---|
| OpenAI | https://platform.openai.com | GPT 系列官方 |
| Anthropic | https://console.anthropic.com | Claude 系列官方 |
| Google Gemini | https://ai.google.dev | Gemini 系列官方 |
| Azure OpenAI | https://azure.microsoft.com/en-us/products/ai-services/openai-service | 微软托管 OpenAI |
| AWS Bedrock | https://aws.amazon.com/bedrock/ | AWS 多模型托管 |
| Google Vertex AI | https://cloud.google.com/vertex-ai | GCP 多模型 |
| Mistral | https://console.mistral.ai | Mistral 官方 |
| Cohere | https://dashboard.cohere.com | Cohere 官方 |
| xAI | https://console.x.ai | Grok 系列官方 |

---

## 五、国际聚合 / 推理平台

| 平台 | 链接 | 说明 |
|---|---|---|
| OpenRouter | https://openrouter.ai | 全球最大的多模型聚合入口之一 |
| Together AI | https://api.together.xyz | 开源模型推理，价格低 |
| Groq | https://console.groq.com | LPU 推理，超低延迟，有免费额度 |
| Fireworks AI | https://fireworks.ai | 开源模型推理，企业级 |
| DeepInfra | https://deepinfra.com | 按量计费，低延迟 |
| Replicate | https://replicate.com | 模型托管与调用 |
| Poe API | https://poe.com/api | Quora 旗下多模型 API |
| Perplexity API | https://docs.perplexity.ai | 搜索增强模型 |

---

## 六、Claude Code / Cursor / Codex CLI 专用站

> 特点：针对编程场景优化，支持 Anthropic 原生协议或 CLI 专用配置，通常提供包月或按量套餐。

| 站点 | 链接 | 说明 |
|---|---|---|
| packyapi | https://www.packyapi.com | 支持 Claude Code / Gemini CLI |
| OfoxAI | https://ofox.ai | 原生 Anthropic 格式，CLI 集成 |
| Code By AI | https://www.codebyai.net | 一个 Key 用于 Claude Code / Codex / Gemini CLI，按 token 计费 |
| lanbuff | https://lanbuff.app | Claude Code / Codex 专属分组，可开票 |
| CloseAI | https://www.closeai-asia.com | Claude Code / CodeX 支持，企业级 |

> 使用提示：Claude Code 等 CLI 工具通常只需设置 `ANTHROPIC_BASE_URL` 与 `ANTHROPIC_AUTH_TOKEN`，具体配置见各站文档。

---

## 七、开源自建方案（自己搭网关）

> 如果你有服务器和上游 Key，可以自己搭一个网关，完全掌控数据与计费。适合团队/企业。

| 项目 | 链接 | 说明 |
|---|---|---|
| new-api | https://github.com/Calcium-Ion/new-api | 主流开源 AI 网关，支持多渠道、计费、令牌管理 |
| one-api | https://github.com/songquanpeng/one-api | 老牌开源网关，生态成熟 |
| LiteLLM | https://github.com/BerriAI/litellm | Python 网关，统一 100+ 模型接口 |
| Portkey Gateway | https://github.com/Portkey-AI/gateway | 生产级 AI 网关，路由/缓存/可观测 |
| Higress AI Gateway | https://github.com/alibaba/higress | 阿里开源，云原生 AI 网关 |
| Bifrost | https://github.com/maximhq/bifrost | 高性能 LLM 网关 |

---

## 八、选型速查表

| 场景 | 建议选择 | 理由 |
|---|---|---|
| 个人试用 / 小额测试 | 支持 ¥10~$1 起充的中转站 | 成本低，方便对比 |
| 日常编程（Cursor / Claude Code） | 原生 Anthropic/OpenAI 协议 + 编程专用分组 | 兼容性好，工具调用稳定 |
| 企业生产 | 有公司主体、可开票、SLA 明确的服务商 | 合规与稳定性优先 |
| 国内模型为主 | 硅基流动 / 阿里云百炼 / 火山方舟等 | 国内线路快，合规 |
| 海外业务 / 多币种 | 支持 USDT / 信用卡的平台或官方 API | 支付方便 |
| 数据敏感 / 团队内部 | 自建 new-api / LiteLLM + 上游官方 Key | 数据可控 |

---

## 九、安全避坑指南

1. **不要大额充值**：新站或小站先小额测试，跑通再追加。
2. **警惕异常低价**：明显低于官方成本的模型，可能被替换成低价模型或存在计费陷阱。
3. **关注缓存计费**：缓存读/写价格差异大，签约前确认缓存价率。
4. **确认充值汇率**：`1 美元额度 = 多少人民币` 直接影响实际成本。
5. **保留账单记录**：选择有清晰账单、可导出明细的平台。
6. **不要把 Token 放前端**：中转站 Token 只放服务端，泄露立即吊销。
7. **敏感数据谨慎**：确认平台是否留存请求内容，必要时使用官方 API 或自建。
8. **发票与合同**：企业采购前确认能否开票、是否有服务协议。

---

## 十、价格与计费科普

- **按 token 计费**：输入（prompt）与输出（completion）通常分开计价，单位多为「美元 / 100 万 tokens」。
- **按次计费**：图像、视频、语音等模型常按调用次数计费。
- **倍率制**：部分中转站用「倍率 × 官方价」计价，倍率 1 通常对应该站设定的基准价，需看清基准。
- **充值汇率**：`1$ 额度 = ¥X`，不同站差异很大，比价时要换算成同一口径。
- **缓存价格**：支持 prompt caching 的模型，缓存命中价格通常为正常价的 10%~25%，签约前确认。
- **最低充值**：不少站支持 $1~¥10 起充，适合小额测试。

---

## 十一、FAQ

**Q：中转站和官方 API 有什么区别？**
A：官方 API 最稳定、价格透明，但可能需要海外支付/网络；中转站提供统一入口、本地支付方式与更低门槛，但需要自行评估稳定性与合规风险。

**Q：一个 Base URL 能调用所有模型吗？**
A：多数中转站兼容 OpenAI 协议，部分同时提供 Anthropic / Gemini 原生协议，具体以各站文档为准。

**Q：如何判断一个站是否靠谱？**
A：看运营时长、是否有公司主体、能否开票、客服响应、公开价格与账单、社区口碑；先小额测试。

**Q：USDT 充值安全吗？**
A：选择支持自动到账且有明确到账规则的平台，付款后核对到账金额；注意链上手续费与到账网络。

**Q：这个仓库收录收费吗？**
A：不收费。收录仅基于公开信息整理，不代表推荐；如需补充或更正请提交 PR / Issue。

---

## 十二、贡献指南

欢迎补充新站点、修正失效链接或更新价格信息，详见 [CONTRIBUTING.md](CONTRIBUTING.md)。

提交格式（示例）：

```markdown
| 站点名 | https://example.com | 一句话特点（协议/模型/支付/起充） |
```

要求：
- 链接必须可访问，站点需与 AI API 相关
- 描述保持客观，不写夸大宣传语
- 不接受纯返利/拉人头链接；如有推广关系请在描述中注明
- 失效站点会被定期移除

---

## 更新日志

- **2026-11-17** — 仓库创建；整理综合中转站、国内平台、国际官方/聚合、CLI 专用站、自建方案与避坑指南。
