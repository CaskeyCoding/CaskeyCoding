# Eric Caskey

**AI reliability engineer and open-source builder.**

I build the checks around AI-assisted software delivery: guardrails that block unsafe output, evaluation gates that fail a build on regression, and written specs that tell an agent what done means.

These are personal projects, built on my own time. The method is in the repositories below.

## Open source

### [Ballast](https://github.com/CaskeyCoding/ballast)

A self-healing RAG system, a guardrails gateway, and an evaluation gate over one shared core. Ballast retrieves and grades its evidence, generates a cited answer, critiques that answer for groundedness, and declines when the evidence does not support one.

### [Loop Harness](https://github.com/CaskeyCoding/loop-harness)

A versioned backlog schema and loop protocol for dependency-ordered agent work. One item per iteration, verification before merge, and a human gate on anything irreversible, billable, or outward-facing.

### [SpecSelf Starter](https://github.com/CaskeyCoding/specself-starter)

A local-first, plain-Markdown template for principles, goals, projects, and reviews, written as specs an AI agent can reason over. The agent surfaces and challenges; the person decides and authors.

### [SpecSelf Local](https://github.com/CaskeyCoding/specself-local)

A local Python CLI and read-only MCP server for explicitly selected SpecSelf Markdown. Zero runtime dependencies and no network transport.

## How I work

- Write the spec and the acceptance checks before the code.
- Give an agent the context for the task in front of it, not the whole documentation tree.
- Put evaluation, review, and release checks in the delivery path, where skipping them fails the build.
- Keep a human on consequential decisions and irreversible actions.

## Experience behind the work

I am a Senior Software Engineer at Amazon, where I architect a multi-region workflow orchestration platform. Its guardrails have run **500,000 cumulative safety checks**.

Earlier at Amazon, I built a monitoring lifecycle platform that brought **3 million monitors** under standardized management. Before that, I spent nine years at Prudential Financial building remote-access, self-service, and cloud reliability systems.

That history shapes the open-source work: deterministic checks before action, explicit ownership, and systems that decline or roll back instead of failing silently.

## Writing

- Case studies and lessons: [caskeycoding.com](https://caskeycoding.com)
- Career history and selected work: [ericcaskey.com](https://ericcaskey.com)

## Connect

- [LinkedIn](https://www.linkedin.com/in/ericrcaskey)
- [Email](mailto:eric@caskeycoding.com)
