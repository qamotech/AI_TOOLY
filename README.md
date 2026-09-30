# AI_TOOLY - Context Extender & Memory Core

AI_TOOLY is a highly advanced, single-file HTML web application designed to act as a localized, persistent memory extension for Large Language Models (LLMs) and their operators. It solves the context window limitation by allowing developers and AI agents to curate, store, search, and dynamically compile knowledge into highly token-efficient prompts.

## Concept & Purpose

When operating complex AI workflows, the context window often becomes cluttered with redundant conversational history or excessive code snippets. AI_TOOLY serves as an **External Cognitive Drive**:
- **Extend Context Usage:** Instead of repeating standard operating procedures or large chunks of code in every prompt, store them in AI_TOOLY as "Memory Blocks".
- **Enhance Memory:** Search your entire history of curated facts, rules, and snippets instantly.
- **Context Compilation:** Select only the memory blocks you need for your current task and compile them into a highly optimized, XML-tagged payload ready for AI ingestion.

## Features (Comprehensive & Extensive)

- **Zero-Dependency Architecture:** Everything (HTML, CSS, JS) is self-contained in `index.html`.
- **Client-Side Storage:** Utilizes IndexedDB and LocalStorage for secure, offline-first data persistence.
- **Token Estimation Engine:** Real-time token heuristics (character/word-based) to ensure your compiled context never exceeds the LLM's limit.
- **Dynamic Theming Engine:** Supports multiple themes (Dark, Light, Cyberpunk, Emerald) with CSS Variables and Glassmorphism aesthetics.
- **Reactive State Management:** Custom Proxy-based PubSub system for lightning-fast UI updates.
- **Export / Import:** Instantly snapshot your entire knowledge base into a JSON file, or restore from a backup.
- **Responsive Layout:** fully optimized for desktops, tablets, and mobile devices.

## How To Use

1. Clone this repository or simply download `index.html`.
2. Open `index.html` in any modern web browser. No server required.
3. Start adding **Memory Blocks** (e.g., "Global Rules", "Project Architecture").
4. When you need to provide context to an AI, select the relevant blocks and click **Compile Context**.
5. Copy the output and paste it into your AI prompt.

## Future Scope

- Integration with Web Workers for heavy text embeddings and local vector search.
- Native filesystem API integration for direct file reads.

## License
MIT
