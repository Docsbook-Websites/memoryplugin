---
title: How MemoryPlugin works
description: The mental model behind a shared AI memory layer - memories, buckets, chat history, and how context reaches your AI without bloating tokens.
---

# How MemoryPlugin works

MemoryPlugin sits between you and the AI tools you already use. Instead of each tool keeping its own private, forgettable context, MemoryPlugin holds one memory you own and injects the relevant parts into whichever AI you are talking to.

## Memories

A memory is a single discrete fact, preference, or piece of context - "I write in a plain, direct voice," "our backend is Postgres on Neon," "this client prefers weekly updates." You capture memories automatically during a conversation or with one click, and you can read, edit, or delete any of them. Nothing is a black box.

## Buckets

Buckets group memories by context - work, personal, a specific project or client. When you talk to your AI inside a given context, MemoryPlugin draws from the right bucket so a client's preferences don't leak into unrelated work.

## Smart Memory and tokens

Injecting every memory into every prompt would waste tokens and dilute the answer. Smart Memory selects only the memories relevant to the current conversation, which keeps injected context lean while still giving the AI what it needs.

## Chat history

Beyond saved memories, MemoryPlugin can import your past conversations from supported platforms and keep them searchable. Ask a question in plain language and it finds the earlier exchange where you worked it out.

## Next

See the model in action in [Getting started](getting-started.md), or compare the ways to connect it in [Integrations](integrations.md).
