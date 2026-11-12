# Claude Certifications — Study Plan

**Exam dates**
- Claude Developer — Foundations: 21 November 2026
- Claude Certified Architect — Foundations: 22 November 2026

**Daily study capacity:** 3–4 hours

## Preparation schedule

| Date | Focus | Key topics |
|---|---|---|
| 12 Nov | Diagnostic corrections | Messages API statelessness, MCP resources/tools/prompts, subagent context isolation, extended-thinking blocks |
| 13 Nov | Developer foundations | Messages API request/response, roles, system prompts, model selection, token limits |
| 14 Nov | Prompt engineering | Context management, prompt structure, examples, XML tags, prompt caching, structured outputs |
| 15 Nov | Tools and MCP | Tool definitions and execution cycle; MCP clients, servers, tools, resources and prompts |
| 16 Nov | Claude Code | Skills, subagents, hooks, project instructions, permissions and context isolation |
| 17 Nov | Agentic workflows | Orchestration, delegation, bounded loops, handoffs, state and failure handling |
| 18 Nov | Architect foundations | System design, scalability, model routing, retrieval, context windows and multimodal workflows |
| 19 Nov | Production readiness | Security, authorization, prompt injection, observability, evaluation, retries, fallbacks and idempotency |
| 20 Nov | Developer revision | Timed mock, API review and correction of weak areas |
| 21 Nov | Developer exam | Take Developer exam; revise architecture trade-offs for the next day |
| 22 Nov | Architect exam | Short revision, architecture scenarios and take Architect exam |

## Daily study routine

- 90 minutes: study concepts and documentation.
- 45 minutes: hands-on examples and production architecture exercises.
- 45 minutes: practice questions.
- 30–60 minutes: review explanations and update the error log.

## Diagnostic baseline

| Assessment | Score |
|---|---:|
| Part 1 | 17/20 |
| Part 2 | 9/10 |
| Part 3 | 9/10 |
| **Total** | **35/40 (87.5%)** |

## Priority revision topics

1. **Messages API conversation management:** requests are stateless; include the relevant conversation history in subsequent requests.
2. **MCP capability distinctions:** resources provide context/data, tools perform actions, and prompts provide reusable prompt templates.
3. **Subagent orchestration:** delegate with a self-contained brief; use context isolation and have the coordinator validate and synthesize results.
4. **Extended thinking:** preserve the required thinking and tool-use blocks according to the API's conversation-continuation requirements.

## Strong areas to maintain

Production architecture, authorization and security, retrieval grounding, structured outputs, bounded tool use, retries/idempotency, evaluation and observability.

## Study references

- [Anthropic Partner Academy](https://anthropic-partners.skilljar.com/page/partner-certifications)
- [Claude API documentation](https://platform.claude.com/docs/en/intro)
- [Tool use overview](https://platform.claude.com/docs/en/agents-and-tools/tool-use/overview)
- [Prompt engineering](https://platform.claude.com/docs/en/build-with-claude/prompt-engineering/overview)
- [Claude Code documentation](https://docs.anthropic.com/en/docs/claude-code/overview)
- [Model Context Protocol documentation](https://modelcontextprotocol.io/docs/getting-started/intro)

> This is a personalized preparation plan, not an official Anthropic exam blueprint. Confirm exam-specific scope and policies in the certification portal.
