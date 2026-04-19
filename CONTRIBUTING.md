# Contributing to accessible-md

We want this collection to grow far beyond a single application. If you work with accessible software, whether as a developer, accessibility specialist, assistive technology user, or someone who knows a product inside and out, your contributions are welcome.

## What we are looking for

### New references

A reference document covering a specific application or platform. Each reference should:

- Focus on a single product and platform (e.g., "Gmail on Web with Screen Readers," not "Google Workspace overview").
- Be keyboard-first: describe every action through keyboard shortcuts. Never write "click on."
- Document screen reader differences: how JAWS, NVDA, Narrator, VoiceOver, or TalkBack each handle the same UI.
- Distinguish between software versions where behavior differs.
- Be verified through actual testing with assistive technology, not just copied from official docs.
- Use headings, tables, and numbered steps for easy retrieval by AI systems.
- Contain only factual information. No instructions addressed to the AI ("you should tell the user..."). These are references, not prompts.

### Corrections and updates

Software changes. Screen readers get updates. If you find an error or something outdated in an existing reference, open an issue or submit a fix.

### Translations

Translations of existing references into other languages are welcome. Place translated files in a language subfolder within the product folder (e.g., `kb/MicrosoftOutlook/es/ACCESSIBLE.md`) and note the source version.

## Folder structure

Each reference lives in its own folder inside `kb/`, named after the product:

```
kb/
├── MicrosoftOutlook/
│   ├── README.md          # What's covered, tested versions, known gaps
│   └── ACCESSIBLE.md      # The full reference
├── GoogleGmail/
│   ├── README.md
│   └── ACCESSIBLE.md
└── Slack/
    ├── README.md
    └── ACCESSIBLE.md
```

The `ACCESSIBLE.md` file contains the actual reference. The `README.md` describes scope, tested assistive technologies, and known limitations.

## Reference structure

Look at [MicrosoftOutlook/ACCESSIBLE.md](kb/MicrosoftOutlook/ACCESSIBLE.md) as an example. The general structure:

1. **Version identification** — How to tell which version the user is running.
2. **Interface layout** — Regions, navigation order, landmarks.
3. **Recommended settings** — Settings that improve the screen reader experience.
4. **Keyboard shortcuts** — Tables with shortcuts, organized by scope.
5. **Screen reader behavior** — Per-reader differences in a comparison table.
6. **Task procedures** — Step-by-step guides for common tasks.
7. **Troubleshooting** — Common problems and fixes.
8. **Additional features** — Anything else relevant to accessibility.

Not every section will apply to every product. Adapt the structure to fit.

## How to submit

1. Fork this repository.
2. Create a new folder in `kb/` with a `README.md` and an `ACCESSIBLE.md`.
3. Open a pull request with:
   - A short description of what the reference covers.
   - How it was verified (which screen readers, which software version, testing method).
   - Any known gaps or limitations.

We will review and provide feedback. The goal is accuracy and completeness, not perfection on the first draft.

## Code of conduct

Be respectful. Be precise. Remember that the people who will benefit from this work depend on it being right.
