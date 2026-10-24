# goose

[goose](https://github.com/aaif-goose/goose) asks LLM services to publish their own custom-provider file, so this is Runcrate's.

## Install

```bash
mkdir -p ~/.config/goose/custom_providers && curl -fsSL https://raw.githubusercontent.com/runcrateai/integrations/main/goose/runcrate.json -o ~/.config/goose/custom_providers/runcrate.json
```

Windows: save the file to `%APPDATA%\Block\goose\config\custom_providers\runcrate.json`.

## Use

```bash
export RUNCRATE_API_KEY=rc_live_...
goose session --provider runcrate --model deepseek-ai/DeepSeek-V4.1-Flash
```

Or in goose Desktop: Settings, Models, Configure providers, **Runcrate**, paste the key (stored in the keychain).

## What the file sets

- `engine: openai`, `base_url: https://api.runcrate.ai/v1/chat/completions`, streaming on
- `api_key_env: RUNCRATE_API_KEY`
- six open models with context windows and per-token prices as billed on a balance:

| Model id | Name |
|---|---|
| `deepseek-ai/DeepSeek-V4.1-Flash` | DeepSeek V4.1 Flash |
| `deepseek-ai/DeepSeek-V4.1-Flash-1017` | DeepSeek V4.1 Flash 1017 |
| `zai-org/GLM-5.3` | GLM-5.3 |
| `zai-org/GLM-5.3-Flash` | GLM-5.3 Flash |
| `Qwen/Qwen3.8-Flash` | Qwen3.8 Flash |
| `openai/gpt-oss-120b` | gpt-oss 120B |

Checked with goose 1.55.0 on 2026-10-24: `goose run --provider runcrate --model deepseek-ai/DeepSeek-V4.1-Flash` answered.
