---
title: How MemoryPlugin works
description: The mental model behind a shared AI memory layer - memories, buckets, chat history, and how relevant context reaches your AI without wasting tokens.
---

# How MemoryPlugin works

MemoryPlugin sits between you and the AI tools you already use. Instead of each tool keeping its own private, forgettable context, MemoryPlugin holds one memory you own and injects the relevant parts into whichever AI you are talking to.

## Memories

A memory is a single discrete fact, preference, or piece of context - "I write in a plain, direct voice," "our backend is Postgres on Neon," "this client prefers weekly updates." You capture memories automatically during a conversation or with one click, and you can read, edit, or delete any of them.

## Injection and recall

When you open an AI tool, MemoryPlugin injects the memories relevant to that conversation. This is [Smart Memory](features/smart-memory.md) - it loads only what is relevant so context stays lean and tokens are not wasted.

## Buckets

[Buckets](features/buckets.md) group memories by context - work, personal, a specific project or client - so the right details surface and nothing bleeds across contexts.

## Chat history

Beyond saved memories, MemoryPlugin imports your past conversations from supported platforms and keeps them searchable. See [chat history](features/chat-history.md).

## Next

Set it up in [Quick setup](getting-started.md), or compare ways to connect it in [integrations](integrations/browser-extension.md).
