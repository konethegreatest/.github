# Motsoeneng Bill Tech · Organization Profile & Health Files

This repository (`Motsoeneng-Bill-Tech/.github`) hosts the public organization profile, health files, and automated engineering telemetry pipelines for **Motsoeneng Bill Tech**.

### 📌 Organization Profile README
The public-facing profile displayed on the [Motsoeneng Bill Tech GitHub Organization](https://github.com/Motsoeneng-Bill-Tech) is located at:
👉 **[`profile/README.md`](profile/README.md)**

---

### ⚙️ Telemetry & Leaderboard Automation
The engineering contribution leaderboard and activity sparklines are updated dynamically via GitHub Actions:
- **Workflow**: [`.github/workflows/update-readme.yml`](.github/workflows/update-readme.yml)
- **Telemetry Engine**: [`.github/scripts/update_leaderboard.py`](.github/scripts/update_leaderboard.py)
- **Assets & Sparklines**: [`assets/graphs/`](assets/graphs/) and [`assets/leaderboard_card.svg`](assets/leaderboard_card.svg)

#### Schedule & Triggers
- Runs automatically every 6 hours (`0 */6 * * *`).
- Can be manually triggered at any time from the **Actions** tab via `workflow_dispatch`.