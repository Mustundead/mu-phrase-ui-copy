<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/cover-dark.svg">
  <img src="assets/cover-light.svg" alt="MU Phrase · UI COPY — Words that make the next step clear." width="100%">
</picture>

<img src="assets/icon.png" alt="MU Phrase" width="112" height="112">

# MU Phrase · UI Copy

**Interface writing that makes the next step clear.**

[中文](README.md) · [Usage](docs/usage.md) · [Skill](SKILL.md) · [MU LABS](https://mustundead.com/#work)

A personal agent skill by [Mustundead](https://github.com/Mustundead), built around MU LABS product practice. The instructions are written in Chinese and work with the requested Chinese and English interface content.

Use it to write, review, or implement controls, state messages, permissions, purchase copy, localization, and accessible text. It preserves the difference between missing and zero, stale and current, pending and complete.

## Install and invoke

Download the [v1.0.1 release](https://github.com/Mustundead/mu-phrase-ui-copy/releases/tag/v1.0.1) or clone this repository. Place its complete folder in the skill directory configured for your assistant. The MU LABS local Codex workflow uses `~/.codex/skills/mu-phrase-ui-copy`; use your host’s documented discovery path elsewhere. Do not overwrite an existing installation without comparing or backing it up.

Invoke `$mu-phrase-ui-copy` in a new session with the target, available evidence, and requested scope. Read [usage](docs/usage.md) for review versus implementation, updates, and limitations. No account, API key, runtime dependency, or background service is included in this package.

## Start with one task

**Review a page.**

```text
Use $mu-phrase-ui-copy. Review the buttons, empty states, and errors on this page. Explain each issue and suggest replacement copy. Do not edit code.
```

**Make the change.**

```text
Use $mu-phrase-ui-copy. Implement the Chinese and English copy changes for this page. Preserve placeholders and behavior, then check the affected resources and running interface.
```

Include the page, screenshot, or project location. A review delivers findings and recommendations; implementation delivers changes and verification results.

## License and sources

The newly written instructions, documentation, and examples are [MIT licensed](LICENSE). Linked third-party materials retain their own terms. See [sources](references/sources.md) for attribution and adaptation boundaries. These are independent MU LABS methods, not an official Apple or OpenAI product.
