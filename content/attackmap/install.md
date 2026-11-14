---
title: "Install"
description: "Install the AttackMap CLI from PyPI or Homebrew, and the macOS app."
weight: 20
---

AttackMap needs Python 3.11 or later. It's on [PyPI](https://pypi.org/project/attackmap/),
together with all 15 official analyzer plugins, and in the
[Homebrew tap](https://github.com/mlaify/homebrew-tap). The same release files are also on
the [M&L AI package index](https://pkg.mlaify.io/) and GitHub.

## Homebrew

The CLI with all 15 official analyzer plugins:

```bash
brew install mlaify/tap/attackmap
```

## uv, pipx or pip, from PyPI

The CLI with every analyzer plugin:

```bash
uv tool install "attackmap[all]"     # or: pipx install "attackmap[all]"
```

Core only (add analyzers later with `attackmap suggest . --install` or `-m <name>`, or
install one directly, e.g. `uv tool install attackmap --with attackmap-analyzer-go`):

```bash
pipx install attackmap
```

The `[llm]` extra adds the Anthropic and OpenAI SDKs for the API backends of the AI
review. The CLI backends (`claude`, `codex`) need nothing extra.

## The macOS app

A native front end that drives the same CLI. The cask installs the CLI too:

```bash
brew install --cask mlaify/tap/attackmap-app
```

Or download the DMG from
[AttackMap-mac releases](https://github.com/mlaify/AttackMap-mac/releases/latest). It
needs macOS 15 or later.

## Check it

```bash
attackmap --help
attackmap modules        # the analyzers installed
attackmap analyze /path/to/repo --output reports
```

Then open `reports/defensive-review.md`. The
[quickstart](https://docs.mlaify.io/attackmap/quickstart/) walks through the reports,
and the [install guide](https://docs.mlaify.io/attackmap/install/) covers CI.
