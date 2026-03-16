# System Prompts Kit

A collection of system prompts for using AI assistants more effectively in professional work. Each prompt is role-specific and designed to shape how the model thinks and responds — not just what it knows.

## Philosophy

Most AI assistants default to being agreeable and verbose. These prompts push in the opposite direction: ask before assuming, show tradeoffs, fix root causes, push back on bad ideas.

## Structure

```
├── backend.md        TypeScript · NestJS · PostgreSQL
├── frontend.md       TypeScript · React · Next.js
├── mobile.md         TypeScript · React Native
├── devops.md         CI/CD · Infrastructure · Cloud · Security
├── marketing.md      Research · Positioning · Content · Growth
├── perplexity.md     Universal research prompt for Perplexity AI
└── ide.md            Base coding guidelines for IDE AI assistants
```

## How to use

Copy the contents of any file into the **system prompt** or **custom instructions** field of your AI assistant.

- **Claude / ChatGPT / Gemini / Grok** → use the role-specific file directly.
- **Perplexity** → use `perplexity.md` regardless of domain.
- **Cursor / Windsurf / IDE assistants** → use `ide.md`.
- **AI agents** → use as a base system prompt for domain-specific agents (e.g. a backend agent, a research agent, a marketing agent).

## Contributing

Prompts are intentionally kept minimal. If you improve one or add a new role, PRs are welcome.