# Claude Code Router

[Claude Code Router](https://github.com/musistudio/claude-code-router) imports a provider from a `ccr://provider` link and previews it before saving. Click it with CCR installed, then add your Runcrate key.

[Import Runcrate into CCR](ccr://provider?name=Runcrate&base_url=https%3A%2F%2Fapi.runcrate.ai%2Fv1&protocol=anthropic_messages&models=deepseek-ai%2FDeepSeek-V4.1-Flash%2Cdeepseek-ai%2FDeepSeek-V4.1-Flash-1017%2Czai-org%2FGLM-5.3%2Czai-org%2FGLM-5.3-Flash%2CQwen%2FQwen3.8-Flash%2Copenai%2Fgpt-oss-120b&source=https%3A%2F%2Fwww.runcrate.ai%2Finference%2Ffree%3Futm_source%3Dclaude-code-router%26utm_medium%3Ddirectory%26utm_campaign%3Dgpu_pricing)

```
ccr://provider?name=Runcrate&base_url=https%3A%2F%2Fapi.runcrate.ai%2Fv1&protocol=anthropic_messages&models=deepseek-ai%2FDeepSeek-V4.1-Flash%2Cdeepseek-ai%2FDeepSeek-V4.1-Flash-1017%2Czai-org%2FGLM-5.3%2Czai-org%2FGLM-5.3-Flash%2CQwen%2FQwen3.8-Flash%2Copenai%2Fgpt-oss-120b&source=https%3A%2F%2Fwww.runcrate.ai%2Finference%2Ffree%3Futm_source%3Dclaude-code-router%26utm_medium%3Ddirectory%26utm_campaign%3Dgpu_pricing
```

It adds `https://api.runcrate.ai/v1` with the Anthropic Messages protocol (CCR derives `https://api.runcrate.ai/v1/messages`); Chat Completions and Responses work on the same key. Models:

| Model id | Name |
|---|---|
| `deepseek-ai/DeepSeek-V4.1-Flash` | DeepSeek V4.1 Flash |
| `deepseek-ai/DeepSeek-V4.1-Flash-1017` | DeepSeek V4.1 Flash 1017 |
| `zai-org/GLM-5.3` | GLM-5.3 |
| `zai-org/GLM-5.3-Flash` | GLM-5.3 Flash |
| `Qwen/Qwen3.8-Flash` | Qwen3.8 Flash |
| `openai/gpt-oss-120b` | gpt-oss 120B |
