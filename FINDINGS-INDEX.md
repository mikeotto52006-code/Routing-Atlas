# Routing Atlas — Research Index

Public research snapshot of source-backed findings. **This index is not a live feed**; check `data/findings.json` for full findings, citations, dates, and open questions.

## How to use

1. Search this index before beginning a new research thread.
2. Read the matching records in [`data/findings.json`](data/findings.json) and check their primary-source URLs.
3. Continue from `open_question` instead of repeating completed research.
4. Contribute proposed corrections or new evidence with source links; do not submit private lab or personal details.

Current snapshot: **45 findings** (exported 2026-11-07).

## Systems covered

### A2A Protocol (3)

- **A2A requires caller scoping while leaving the authorization model to each agent** — `a2a-v100-authorization-agent-defined` · [Source](https://a2a-protocol.org/v1.0.0/specification/#131-data-access-and-authorization-scoping)
- **A2A cancellation requests do not guarantee cancellation** — `a2a-v100-cancellation-not-completion` · [Source](https://a2a-protocol.org/v1.0.0/specification/#315-cancel-task)
- **A2A message-send deduplication is optional** — `a2a-v100-send-idempotency-optional` · [Source](https://a2a-protocol.org/v1.0.0/specification/#331-idempotency)

### Agent Zero (1)

- **Agent Zero configures main and utility models separately** — `agent-zero-main-utility` · [Source](https://github.com/agent0ai/agent-zero)

### AI Workshop Jarvis (4)

- **Hands-free command selects a named cloud model in the UI** — `jarvis-workshop-cloud-brain-demo` · [Source](https://www.youtube.com/watch?v=Acw0NtkyNtM&t=81s)
- **Spoken command changes voice while Qwen remains selected** — `jarvis-workshop-independent-voice` · [Source](https://www.youtube.com/watch?v=BgpRjk4Yoqk&t=275s)
- **The creator offers prompts and build instructions** — `jarvis-workshop-lite-build-materials` · [Source](https://www.skool.com/aiworkshop-lite/about)
- **Spoken local model selection appears in the demo** — `jarvis-workshop-local-brain-demo` · [Source](https://www.youtube.com/watch?v=BgpRjk4Yoqk)

### Anthropic multi-agent research (1)

- **Anthropic reports substantial multi-agent token overhead and limited coding parallelism** — `anthropic-multiagent-token-overhead` · [Source](https://www.anthropic.com/engineering/multi-agent-research-system)

### AnythingLLM (3)

- **Document indexing uses a system-wide model** — `anythingllm-global-embedder` · [Source](https://docs.anythingllm.com/setup/embedder-configuration/overview)
- **The routing model can receive history before a worker answers** — `anythingllm-router-classifier-history` · [Source](https://docs.anythingllm.com/model-router/overview)
- **A matched route can persist across follow-ups** — `anythingllm-router-sticky-window` · [Source](https://docs.anythingllm.com/model-router/setup)

### ByteRover / Hermes Agent (1)

- **ByteRover V3 and V4 use different integration workflows** — `byterover-v4-9c35d8-v3-migration-boundary` · [Source](https://github.com/campfirein/skills/blob/9c35d87cb823c53fe56c1a8d4f1c0912abb67c05/skills/byterover/migrate-v3-to-v4.md#L8)

### ByteRover V4 (2)

- **Telemetry bootstrap preserves a valid opt-out but enables missing or malformed settings** — `byterover-v4-9c35d8-analytics-default-bootstrap` · [Source](https://github.com/campfirein/skills/blob/9c35d87cb823c53fe56c1a8d4f1c0912abb67c05/skills/byterover/scripts/sync-daemon.mjs#L17455)
- **The telemetry projection can retain query text and topic metadata** — `byterover-v4-9c35d8-telemetry-query-payload` · [Source](https://github.com/campfirein/skills/blob/9c35d87cb823c53fe56c1a8d4f1c0912abb67c05/skills/byterover/scripts/sync-daemon.mjs#L17605)

### Hermes Agent (18)

- **A pinned Hermes checkout can resolve a live plugin catalog** — `hermes-bf0203-live-plugin-catalog` · [Source](https://github.com/NousResearch/hermes-agent/blob/bf0203a794a07aac3ff764972ab9087baa4e4f4e/hermes_cli/plugin_catalog.py)
- **Hermes labels recalled context as authoritative reference data** — `hermes-bf0203-recall-authority-wrapper` · [Source](https://github.com/NousResearch/hermes-agent/blob/bf0203a794a07aac3ff764972ab9087baa4e4f4e/agent/memory_context.py#L169)
- **Delegated agents inherit a bounded set of tools** — `hermes-delegation-tool-inheritance` · [Source](https://github.com/NousResearch/hermes-agent/blob/main/website/docs/user-guide/features/delegation.md)
- **Kanban workers can execute remotely while board tools stay local** — `hermes-kanban-remote-terminal-central-board` · [Source](https://github.com/NousResearch/hermes-agent/blob/main/website/docs/user-guide/features/kanban.md)
- **Kanban explicitly does not support a shared multi-host dispatcher** — `hermes-kanban-single-host-dispatcher-boundary` · [Source](https://github.com/NousResearch/hermes-agent/blob/main/website/docs/user-guide/features/kanban.md)
- **Hermes documents direct LM Studio support** — `hermes-lm-studio-provider` · [Source](https://github.com/NousResearch/hermes-agent/blob/main/website/docs/integrations/providers.md)
- **Main and auxiliary model settings are separate** — `hermes-main-aux-routing` · [Source](https://hermes-agent.nousresearch.com/docs/user-guide/configuring-models)
- **Stored memories can enter model context** — `hermes-memory-session-snapshot` · [Source](https://github.com/NousResearch/hermes-agent/blob/main/website/docs/user-guide/features/memory.md)
- **An in-session switch reuses conversation context** — `hermes-mid-session-context` · [Source](https://hermes-agent.nousresearch.com/docs/user-guide/configuring-models)
- **One-turn provider switch retains session context** — `hermes-model-once` · [Source](https://hermes-agent.nousresearch.com/docs/reference/slash-commands)
- **Child transcript stays with the launching profile** — `hermes-profile-child-transcript` · [Source](https://hermes-agent.nousresearch.com/docs/developer-guide/delegation-provider-plugin)
- **Hermes SSH terminal backend uses explicit remote credentials** — `hermes-ssh-backend-credentials-security` · [Source](https://github.com/NousResearch/hermes-agent/blob/main/website/docs/user-guide/security.md)
- **Hermes skips dangerous-command approval in container terminal backends** — `hermes-v0225-docker-approval-boundary` · [Source](https://github.com/NousResearch/hermes-agent/blob/v0.22.5/website/docs/user-guide/security.md)
- **Hermes Python execution defaults to project working directory, not OS isolation** — `hermes-v0225-execute-code-project-default` · [Source](https://github.com/NousResearch/hermes-agent/blob/v0.22.5/tools/code_execution_tool.py#L3243)
- **Hermes file-write safety applies to named file tools, not a VM boundary** — `hermes-v0225-file-write-scope` · [Source](https://github.com/NousResearch/hermes-agent/blob/v0.22.5/website/docs/user-guide/security.md)
- **Hermes warns against two agents sharing one memory home** — `hermes-v0225-memory-multiwriter-warning` · [Source](https://github.com/NousResearch/hermes-agent/blob/v0.22.5/website/docs/user-guide/features/memory.md)
- **Hermes memory writes are automatic unless approval is enabled** — `hermes-v0225-memory-write-gate` · [Source](https://github.com/NousResearch/hermes-agent/blob/v0.22.5/website/docs/user-guide/features/memory.md)
- **v0.22.5 documents spoken interruption** — `hermes-v0225-voice-interrupt` · [Source](https://github.com/NousResearch/hermes-agent/blob/v0.22.5/website/docs/user-guide/features/voice-mode.md)

### Hermes Agent / Hindsight (2)

- **Disabling automatic turn retention does not gate built-in memory mirroring** — `hindsight-d952b6-builtin-mirror-gate` · [Source](https://github.com/vectorize-io/hindsight/blob/d952b6e655fccab4581ee0722b51c5f103873d12/hindsight-integrations/hermes/__init__.py#L1865)
- **Hindsight's Hermes recall formatter emits result text** — `hindsight-d952b6-hermes-recall-text-projection` · [Source](https://github.com/vectorize-io/hindsight/blob/d952b6e655fccab4581ee0722b51c5f103873d12/hindsight-integrations/hermes/__init__.py#L1600)

### Home Assistant Assist (1)

- **Two wake phrases can select local and cloud assistants** — `home-assistant-dual-wake-2025-10` · [Source](https://community.home-assistant.io/t/voice-chapter-11-multilingual-assistants-are-here/943009)

### isair/Jarvis (1)

- **A separate Jarvis desktop app supports Linux and LM Studio** — `isair-jarvis-linux-model-roles` · [Source](https://github.com/isair/jarvis)

### LibreChat (2)

- **User memory can enter each new message** — `librechat-memory-context` · [Source](https://www.librechat.ai/docs/features/memory)
- **LibreChat documents a local Ollama endpoint** — `librechat-ollama-endpoint` · [Source](https://www.librechat.ai/docs/configuration/librechat_yaml/ai_endpoints/ollama)

### Model Context Protocol (1)

- **MCP tool annotations require a trusted source** — `mcp-20251125-tool-annotations-untrusted` · [Source](https://modelcontextprotocol.io/specification/2025-11-25/server/tools)

### OpenAI Agents SDK (2)

- **OpenAI Agents SDK handoffs pass conversation history by default** — `openai-agents-handoff-history-default` · [Source](https://openai.github.io/openai-agents-python/handoffs/)
- **Manager-as-tool and handoff patterns have different control ownership** — `openai-agents-manager-vs-handoff` · [Source](https://openai.github.io/openai-agents-python/multi_agent/)

### OpenClaw (3)

- **The gateway assumes mutually trusted operators** — `openclaw-gateway-trust` · [Source](https://docs.openclaw.ai/gateway/security)
- **OpenClaw documents LM Studio and Ollama backends** — `openclaw-local-model-servers` · [Source](https://docs.openclaw.ai/gateway/local-models)
- **A non-default session model can fail closed** — `openclaw-session-model-pin` · [Source](https://docs.openclaw.ai/concepts/models)

