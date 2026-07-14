---
title: MemoryPlugin FAQ
description: Common questions about a shared AI memory - privacy, supported tools, chat-history import, editing memories, and how injection works.
---

# Frequently asked questions

## Which AI tools does MemoryPlugin support?

More than 21, including ChatGPT, Claude, Gemini, Grok, DeepSeek, Perplexity, Mistral, Poe, and LibreChat through the browser extension, plus Claude Desktop, Cursor, and Windsurf through the MCP server. See [supported platforms](platforms.md).

## Is my memory shared across all of them?

Yes - a fact you save in one tool is available in the others, instead of being locked to a single app.

## Can I edit or delete a memory?

Yes. Every memory is a discrete, editable item you can read, change, or remove. It is not an opaque auto-summary.

## Does it slow down or bloat my prompts?

No. [Smart Memory](features/smart-memory.md) injects only the memories relevant to the current conversation.

## Can I bring in my past conversations?

Yes. Import [chat history](features/chat-history.md) from supported platforms and search it in plain language. Imports are opt-in.

## What about privacy?

Data is encrypted in transit and at rest, is not used for model training, and you can export or delete it at any time.

## How do I get my API token?

Your authentication token is available in your dashboard after you create an account.

## Related

- Back to [How it works](concepts.md)
- [Quick setup](getting-started.md)
