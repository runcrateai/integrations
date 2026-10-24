# Runcrate integrations

Ready-made configs that point coding agents and model switchers at [Runcrate](https://www.runcrate.ai/inference/free?utm_source=github-integrations&utm_medium=directory&utm_campaign=gpu_pricing). Open models are free with your GitHub account; every other model is billed per token from a prepaid balance.

You need a Runcrate API key (`rc_live_...`): sign in with GitHub at https://www.runcrate.ai/dashboard/api-keys and create one.

| Tool | One-line install | Details |
|---|---|---|
| [goose](https://github.com/aaif-goose/goose) | `mkdir -p ~/.config/goose/custom_providers && curl -fsSL https://raw.githubusercontent.com/runcrateai/integrations/main/goose/runcrate.json -o ~/.config/goose/custom_providers/runcrate.json` | [goose/](goose/) |
| [CC Switch](https://github.com/farion1231/cc-switch) (Claude Code, Codex, OpenCode) | open a `ccswitch://` link from [cc-switch/](cc-switch/) | [cc-switch/](cc-switch/) |
| [Claude Code Router](https://github.com/musistudio/claude-code-router) | open the `ccr://provider` link from [claude-code-router/](claude-code-router/) | [claude-code-router/](claude-code-router/) |
| [Hermes Agent](https://github.com/NousResearch/hermes-agent) | `hermes plugins install runcrateai/hermes-runcrate/model-providers/runcrate` | [runcrateai/hermes-runcrate](https://github.com/runcrateai/hermes-runcrate) |

## The API

| | |
|---|---|
| OpenAI-compatible base URL | `https://api.runcrate.ai/v1` (chat completions and Responses) |
| Anthropic Messages base URL (Claude Code `ANTHROPIC_BASE_URL`) | `https://api.runcrate.ai` |
| Model list | `GET https://api.runcrate.ai/v1/models` (no key needed) |
| Auth | `Authorization: Bearer rc_live_...` (Messages also takes `x-api-key`) |

## Open models used in these configs

| Model id | Name |
|---|---|
| `deepseek-ai/DeepSeek-V4.1-Flash` | DeepSeek V4.1 Flash |
| `deepseek-ai/DeepSeek-V4.1-Flash-1017` | DeepSeek V4.1 Flash 1017 |
| `zai-org/GLM-5.3` | GLM-5.3 |
| `zai-org/GLM-5.3-Flash` | GLM-5.3 Flash |
| `Qwen/Qwen3.8-Flash` | Qwen3.8 Flash |
| `openai/gpt-oss-120b` | gpt-oss 120B |

More tools: see the setup prompt at https://www.runcrate.ai/inference/free?utm_source=github-integrations&utm_medium=directory&utm_campaign=gpu_pricing (Claude Code, Codex, OpenCode, Cline, Roo Code, Kilo Code, Cursor).

## License

MIT, Aeonmind LLC.
