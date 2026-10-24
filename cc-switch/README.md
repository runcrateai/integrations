# CC Switch

[CC Switch](https://github.com/farion1231/cc-switch) imports a provider from a `ccswitch://` link. Click one (CC Switch must be installed), paste your Runcrate key in the confirm dialog, and switch.

| App | Link | Endpoint |
|---|---|---|
| Claude Code | [Import into CC Switch](ccswitch://v1/import?resource=provider&app=claude&name=Runcrate&endpoint=https%3A%2F%2Fapi.runcrate.ai&homepage=https%3A%2F%2Fwww.runcrate.ai%2Finference%2Ffree%3Futm_source%3Dcc-switch%26utm_medium%3Ddirectory%26utm_campaign%3Dgpu_pricing&model=deepseek-ai%2FDeepSeek-V4.1-Flash&haikuModel=zai-org%2FGLM-5.3-Flash&sonnetModel=deepseek-ai%2FDeepSeek-V4.1-Flash&opusModel=zai-org%2FGLM-5.3) | `https://api.runcrate.ai` (Anthropic Messages) |
| Codex | [Import into CC Switch](ccswitch://v1/import?resource=provider&app=codex&name=Runcrate&endpoint=https%3A%2F%2Fapi.runcrate.ai%2Fv1&homepage=https%3A%2F%2Fwww.runcrate.ai%2Finference%2Ffree%3Futm_source%3Dcc-switch%26utm_medium%3Ddirectory%26utm_campaign%3Dgpu_pricing&model=deepseek-ai%2FDeepSeek-V4.1-Flash&apiFormat=openai_responses) | `https://api.runcrate.ai/v1` (Responses) |
| OpenCode | [Import into CC Switch](ccswitch://v1/import?resource=provider&app=opencode&name=Runcrate&endpoint=https%3A%2F%2Fapi.runcrate.ai%2Fv1&homepage=https%3A%2F%2Fwww.runcrate.ai%2Finference%2Ffree%3Futm_source%3Dcc-switch%26utm_medium%3Ddirectory%26utm_campaign%3Dgpu_pricing&model=deepseek-ai%2FDeepSeek-V4.1-Flash&apiFormat=openai_chat) | `https://api.runcrate.ai/v1` (OpenAI compatible) |

Claude Code mapping: main and Sonnet `deepseek-ai/DeepSeek-V4.1-Flash`, Opus `zai-org/GLM-5.3`, Haiku `zai-org/GLM-5.3-Flash`.

GitHub renders custom URL schemes as plain text in some views; if a link does not open, copy it into your browser's address bar.

Raw links:

```
ccswitch://v1/import?resource=provider&app=claude&name=Runcrate&endpoint=https%3A%2F%2Fapi.runcrate.ai&homepage=https%3A%2F%2Fwww.runcrate.ai%2Finference%2Ffree%3Futm_source%3Dcc-switch%26utm_medium%3Ddirectory%26utm_campaign%3Dgpu_pricing&model=deepseek-ai%2FDeepSeek-V4.1-Flash&haikuModel=zai-org%2FGLM-5.3-Flash&sonnetModel=deepseek-ai%2FDeepSeek-V4.1-Flash&opusModel=zai-org%2FGLM-5.3
```

```
ccswitch://v1/import?resource=provider&app=codex&name=Runcrate&endpoint=https%3A%2F%2Fapi.runcrate.ai%2Fv1&homepage=https%3A%2F%2Fwww.runcrate.ai%2Finference%2Ffree%3Futm_source%3Dcc-switch%26utm_medium%3Ddirectory%26utm_campaign%3Dgpu_pricing&model=deepseek-ai%2FDeepSeek-V4.1-Flash&apiFormat=openai_responses
```

```
ccswitch://v1/import?resource=provider&app=opencode&name=Runcrate&endpoint=https%3A%2F%2Fapi.runcrate.ai%2Fv1&homepage=https%3A%2F%2Fwww.runcrate.ai%2Finference%2Ffree%3Futm_source%3Dcc-switch%26utm_medium%3Ddirectory%26utm_campaign%3Dgpu_pricing&model=deepseek-ai%2FDeepSeek-V4.1-Flash&apiFormat=openai_chat
```
