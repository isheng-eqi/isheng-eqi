<p align="center">
  <img src="taiji.png" width="180" alt="☯" />
</p>


☯ isheng-eqi

> AI-native — I don't write code. I direct AI to produce it.
> Reverse-engineering AI agents. Redefining the human-tool relationship.


## Contributions

### Hermes — 10 commits · [commits](https://github.com/NousResearch/hermes-agent/commits?author=isheng-eqi)

Agent Core
[#97167](https://github.com/NousResearch/hermes-agent/pull/97167)
fix(agent): tool-pair sanitizers (salvage #55845 + #78063 + #59434)
[#60120](https://github.com/NousResearch/hermes-agent/pull/60120)
fix(interrupt/auth): prevent /stop swallow (incl. Bedrock) and empty-provider credential corruption
[#83009](https://github.com/NousResearch/hermes-agent/pull/83009)
fix(process): reject non-positive wait timeouts (salvage #60004)

Scheduling
[#59524](https://github.com/NousResearch/hermes-agent/pull/59524)
fix(cron): durable run-claim prevents one-shot double-execution
[#59447](https://github.com/NousResearch/hermes-agent/pull/59447)
fix(cron): reject past one-shot in update_job fallback + resume_job

Gateway / Voice
[#73517](https://github.com/NousResearch/hermes-agent/pull/73517)
fix(discord): voice correctness — callback wiring, warm-up clip fix, threading, drain, configurable timeouts


### Pydantic-AI — 4 merged

[#6373](https://github.com/pydantic/pydantic-ai/pull/6373)
ConcurrencyLimit max_queued validation ·
[#6375](https://github.com/pydantic/pydantic-ai/pull/6375)
Tool max_retries validation ·
[#6377](https://github.com/pydantic/pydantic-ai/pull/6377)
ToolOutput max_retries validation ·
[#6383](https://github.com/pydantic/pydantic-ai/pull/6383)
Agent tool_timeout validation


### Dify — 2 merged

[#38447](https://github.com/langgenius/dify/pull/38447)
drop redundant len(tag_ids)==0 check ·
[#38448](https://github.com/langgenius/dify/pull/38448)
raise clear error on unsupported execute_code language ·

[#767](https://github.com/langgenius/dify-plugin-daemon/pull/767)
dify-plugin-daemon — fallback to lowercase proxy env vars


### Heym — 1 merged

[#292](https://github.com/heymrun/heym/pull/292)
thread-safe node input reads + JSON parse error handling


## Projects

[Janus](https://github.com/isheng-eqi/janus-agent) — AI agent framework, four-role architecture
[agentcanary](https://github.com/isheng-eqi/agentcanary) — Agent security red-team toolkit
[claude-code-reverse-engineering](https://github.com/isheng-eqi/claude-code-reverse-engineering) — Full binary reverse of Claude Code (215MB)
[elder-pill](https://github.com/isheng-eqi/elder-pill) — Android medication reminder with deep alarm integration
[media-crawler-easy](https://github.com/isheng-eqi/media-crawler-easy) — Multi-platform social media scraper
[pure-chat](https://github.com/isheng-eqi/pure-chat) — Zero-injection, zero-prompt, multi-API chat


## Writing

[CSDN](https://blog.csdn.net/2401_87426897)


## Direction

Reverse-engineering AI agents · Agent architecture design · Open-source contribution
From formlessness, form. Taiji yields two poles.


[Twitter](https://twitter.com/ishengeqi) · [Email](mailto:ishengeqi@163.com)
