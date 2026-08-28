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
[#60018](https://github.com/NousResearch/hermes-agent/pull/60018)
fix: prevent /stop signal loss and empty provider credential corruption
[#60004](https://github.com/NousResearch/hermes-agent/pull/60004)
fix: reject non-positive process timeout; clear hint for read_file past EOF

Scheduling
[#59446](https://github.com/NousResearch/hermes-agent/pull/59446)
fix(cron): prevent double-execution of one-shot jobs across concurrent schedulers
[#59428](https://github.com/NousResearch/hermes-agent/pull/59428)
fix(cron): reject past one-shot timestamps in update_job + resume_job

Gateway / Voice
[#61407](https://github.com/NousResearch/hermes-agent/pull/61407)
fix(discord): wire voice input callback at adapter connect time


### Pydantic-AI — 4 merged

[#6373](https://github.com/pydantic/pydantic-ai/pull/6373)
ConcurrencyLimit max_queued validation ·
[#6375](https://github.com/pydantic/pydantic-ai/pull/6375)
Tool max_retries validation ·
[#6377](https://github.com/pydantic/pydantic-ai/pull/6377)
ToolOutput max_retries validation ·
[#6383](https://github.com/pydantic/pydantic-ai/pull/6383)
Agent tool_timeout validation


### Dify — 3 merged

[#38447](https://github.com/langgenius/dify/pull/38447)
drop redundant len(tag_ids)==0 check ·
[#38448](https://github.com/langgenius/dify/pull/38448)
raise clear error on unsupported execute_code language ·
[#38494](https://github.com/langgenius/dify/pull/38494)
fix provider_type in plugin dependency ids

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
