# accessible-md

Accessibility references for AI systems.

## What is this?

AI assistants are used every day by people with disabilities through voice interfaces, screen readers, and other assistive technology. But most AI systems lack the detailed, structured knowledge needed to actually help with specific software and workflows.

**accessible-md** is a collection of accessibility reference documents built for AI consumption. Each reference covers a specific application or platform, documenting keyboard shortcuts, screen reader behavior, step-by-step procedures, settings paths, and common problems that real users run into every day.

These are not tutorials for humans. They are structured knowledge files designed to be dropped into system prompts, RAG pipelines, or tool-augmented AI systems. When a person who is blind asks "how do I create a calendar event in Outlook using JAWS," the AI should have a precise, tested answer rather than a generic guess.

## Why this matters

Most accessibility documentation on the web is written for sighted readers, scattered across support pages, and often outdated or incomplete when it comes to assistive technology. Screen reader behavior varies significantly between JAWS, NVDA, and Narrator. "New" and "Classic" versions of the same app can have completely different keyboard paths. A shortcut that works in one context may do something else entirely in another.

AI systems that try to help with accessibility tasks without this kind of detailed reference frequently give wrong answers, suggest mouse-based actions to people who use screen readers, or miss critical differences between software versions.

These references are built from hands-on testing, official documentation, community knowledge, and real conversations with assistive technology users. Every shortcut and procedure has been verified.

## Available references

| Reference | Application | Covers |
|-----------|------------|--------|
| [Microsoft Outlook](kb/MicrosoftOutlook/) | Outlook for Windows (New + Classic) | JAWS, NVDA, Narrator, Magnifier, high contrast, Immersive Reader. Keyboard shortcuts, interface layout, settings, 18+ task procedures, calendar grid navigation, troubleshooting. |

## How to use these references

**In a system prompt:** Include the relevant reference file (or sections of it) directly in your AI system's context. The documents are structured with clear headings and tables so that language models can find specific information quickly.

**In a RAG pipeline:** Index the reference files and retrieve relevant sections based on user queries. The heading structure and table format work well with chunk-based retrieval.

**As training or fine-tuning data:** The references can be used as high-quality accessibility knowledge for model training.

## Contributing

We want this collection to grow. If your organization builds or supports accessible software, consider contributing a reference for your product.

### What makes a good reference

- **Keyboard-first.** Every action described through keyboard shortcuts, never "click on."
- **Screen reader-specific.** Document how each major screen reader (JAWS, NVDA, Narrator, VoiceOver, TalkBack) behaves differently with the same UI.
- **Version-aware.** Clearly distinguish between software versions where behavior differs.
- **Verified.** Every shortcut and procedure tested with actual assistive technology.
- **Structured for retrieval.** Use headings, tables, and numbered steps. Avoid long prose paragraphs.
- **No instructions to the AI.** These are factual references, not prompt engineering. Keep behavioral instructions out.

### How to contribute

1. Fork this repository.
2. Create a new folder in `kb/` named after the product (e.g., `kb/Edge/`, `kb/Slack/`, `kb/VSCode/`).
3. Add an `ACCESSIBLE.md` file with the reference content, following the structure of existing references.
4. Add a `README.md` describing what the reference covers, which assistive technologies were tested, and any known gaps.
5. Open a pull request with a description of the reference and how it was verified.

We especially welcome references for:
- Web browsers (Chrome, Firefox, Edge) with screen readers
- Slack, Teams, Zoom, and other communication tools
- Mobile platforms (iOS VoiceOver, Android TalkBack)
- Development tools (VS Code, terminal emulators)
- Operating system navigation (Windows, macOS)
- PDF readers and document editors
- Banking, healthcare, and government service portals

## Who is behind this

This project was started by [Frontierz](https://frontierz.com) in partnership with Microsoft. The first reference was built as part of an accessibility initiative to bring AI-powered support to people who are blind or have low vision.

We believe accessibility knowledge should be open. The more AI systems have access to accurate, detailed references, the better the experience for everyone who depends on assistive technology.

## License

This project is released under [CC0 1.0 Universal](LICENSE.md) (public domain). Use it however you want, no attribution required.
