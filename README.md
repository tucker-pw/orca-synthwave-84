# SynthWave '84 for Orca

A Synthwave-inspired neon dark theme for [Orca](https://onorca.dev): interface, editor, and terminal. Ported from [Robb Owen's SynthWave '84](https://github.com/robb0wen/synthwave-vscode) VS Code theme.

Requires **Orca 1.4.245 or newer**.

## Install

1. Open **Settings → Plugins**.
2. Choose **Add plugin → From a Git URL…** and enter:

   `https://github.com/tucker-pw/orca-synthwave-84#v1.0.0`

   Keep the `#v1.0.0` tag — Orca requires a release tag or commit hash to install from Git.
3. In **Settings → Appearance**, choose **SynthWave '84** as the app theme.
4. Choose the matching **SynthWave '84** terminal palette.

For local development, clone the repo and add its root via **Settings → Plugins → Development folders…**.

## What differs from the VS Code original

SynthWave '84's signature **neon glow** is a CSS injection in VS Code, not a theme color. Orca's content-only theme format reproduces the palette — the deep purple surfaces, hot-pink variables, cyan functions, yellow keywords — but not the glow/bloom effect.

Orca also exposes fewer individual UI colors than VS Code, so some controls derive their colors from the app palette.

## Attribution

An unofficial Orca port of [SynthWave '84](https://github.com/robb0wen/synthwave-vscode) by **Robb Owen** (`robb0wen`). The upstream MIT license, including Copyright © 2019 Robb Owen, is preserved in [LICENSE](LICENSE).
