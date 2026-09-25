# Cobrain plugin for Claude

One memory for all your AIs. [Cobrain](https://cobrain.space) keeps your notes, decisions and context as Markdown in a brain that Claude, ChatGPT, Codex and any MCP client read and write.

This plugin adds:

- **the Cobrain connector** (`https://cobrain.space/mcp`, remote MCP with OAuth sign-in);
- **the `cobrain` skill**, which teaches Claude when to load context and how to save to the brain without overwriting it.

## Install

In Claude Code:

```
/plugin marketplace add alessandromoretti90/cobrain-plugin
/plugin install cobrain@cobrain
```

On first use Claude opens the Cobrain sign-in page. A free account is enough.

## Links

- Tools reference: https://cobrain.space/guides
- Privacy policy: https://cobrain.space/privacy
- Support: hi@cobrain.space
