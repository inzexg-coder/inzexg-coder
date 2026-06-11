<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/ameni-logo.svg">
    <img src="assets/ameni-logo.svg" alt="Ameni" width="110">
  </picture>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Ameni-Agent-4CAF50?labelColor=222">
  <img src="https://img.shields.io/badge/domain-node_based_visual_programming-2196F3?labelColor=222">
  <img src="https://img.shields.io/badge/domain-vs_kernel_fix-5C2D91?labelColor=222">
  <img src="https://img.shields.io/badge/domain-telegram_analytics-26A5E4?labelColor=222">
  <img src="https://img.shields.io/badge/arch_linux-AUR_support-1793D1?logo=archlinux&labelColor=222">
</p>

<p align="center">
  <b><a href="https://github.com/inzexg-coder/Amenodes">Amenodes</a></b>
  &middot;
  <b><a href="https://github.com/inzexg-coder/ameni-vs-kernel">VS Kernel</a></b>
  &middot;
  <b><a href="https://github.com/inzexg-coder/ameni-tg-parser">Ameni TG Parser</a></b>
</p>

<br>

## Ameni

Multi-domain automation agent designed to consolidate development workflows across independent projects. Ameni provides a unified CLI interface for three domains:

* **Node-based visual programming** — real-time data flow construction and mathematical computation
* **Visual Studio build repair** — diagnostic toolchain for resolving linker errors (LNK2019, LNK1104) and misconfigured VC++ directories
* **Telegram chat analysis** — statistical processing of exported conversation history with per-hour, per-day, per-sender breakdowns

The agent pattern follows a stateless command architecture: each invocation reads input, produces structured output, and exits. There is no daemon process.

<br>

## Projects

### [Amenodes](https://github.com/inzexg-coder/Amenodes)

Node-based visual programming language implemented in JavaScript for data analysis and mathematical computation. Replaces spreadsheet workflows with a directed-graph editor where nodes represent operations and edges represent data flow. Supports real-time execution, diagram export/import, and performance profiling.

<a href="https://next.ossinsight.io/widgets/official/analyze-repo-pushes-and-commits-per-month?repo_id=1224446727" target="_blank">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://next.ossinsight.io/widgets/official/analyze-repo-pushes-and-commits-per-month/thumbnail.png?repo_id=1224446727&image_size=auto&color_scheme=dark" width="100%">
    <img alt="Amenodes commit activity" src="https://next.ossinsight.io/widgets/official/analyze-repo-pushes-and-commits-per-month/thumbnail.png?repo_id=1224446727&image_size=auto&color_scheme=dark" width="100%">
  </picture>
</a>


### [FIDE Rating Calculator](https://github.com/inzexg-coder/fide-rating-calc)

FIDE rating estimation from Lichess and Chess.com games using Anchor method.
REST API, CLI agent, and web interface.

**Live:** [amenoke.ru/fide-estimator](https://amenoke.ru/fide-estimator/)

**Key capabilities:**
- Anchor-based estimation via titled opponents
- Regression model fallback (R^2 > 0.998)
- Crowdsourced offset accumulation
- CLI agent: `ameni fide estimate <username>`
- REST API: POST /api/estimate

### [Ameni VS Kernel](https://github.com/inzexg-coder/ameni-vs-kernel)

Configuration archive and step-by-step guide for resolving Microsoft Visual Studio build-system failures. Covers Windows SDK detection, vcxproj normalization, property sheet injection, and per-version VS configuration snapshots (2017, 2022, 2025). Each resolution step includes diagnostic commands, expected outputs, and error-handling procedures.

**Key capabilities:**
- Cross-platform diagnostics (Windows + Linux)
- Reference configuration comparison
- PowerShell and bash CLI agent
- Arch Linux PKGBUILD / AUR support

### [Ameni TG Parser](https://github.com/inzexg-coder/ameni-tg-parser)

Telegram chat export analyzer with dual web and CLI interfaces. Processes result.json exports from Telegram Desktop and produces statistical reports including message frequency, participant activity, response-time distribution, and media-type breakdown. The web version renders interactive charts; the CLI version outputs formatted tables and histograms.

**CLI commands (Arch Linux: `sudo pacman -S nodejs npm`):**
- `ameni tg stats` — full chat statistics
- `ameni tg top` — top senders with histogram
- `ameni tg activity` — hourly and weekday distribution
- `ameni tg media` — media type breakdown

<br>

## Activity

<a href="https://next.ossinsight.io/widgets/official/compose-user-dashboard-stats?user_id=244792661" target="_blank">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://next.ossinsight.io/widgets/official/compose-user-dashboard-stats/thumbnail.png?user_id=244792661&image_size=auto&color_scheme=dark" width="100%">
    <img alt="Dashboard stats" src="https://next.ossinsight.io/widgets/official/compose-user-dashboard-stats/thumbnail.png?user_id=244792661&image_size=auto&color_scheme=dark" width="100%">
  </picture>
</a>

<br>

## Contact

<p align="center">
  <a href="https://t.me/Amenoke">
    <img src="https://img.shields.io/badge/Telegram-amenoke-26A5E4?style=flat-square&logo=telegram&labelColor=222">
  </a>
  <a href="mailto:amenokeakira@gmail.com">
    <img src="https://img.shields.io/badge/Email-amenokeakira@gmail.com-EA4335?style=flat-square&logo=gmail&labelColor=222">
  </a>
  <a href="https://github.com/inzexg-coder">
    <img src="https://img.shields.io/badge/GitHub-inzexg__coder-181717?style=flat-square&logo=github&labelColor=222">
  </a>
</p>
