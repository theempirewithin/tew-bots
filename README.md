<p align="center">
  <img src="assets/bot.gif" width="600" alt="TEW-Bots: the logo bot in a suit, with other bots in different shapes and colours behind it" />
</p>

<h1 align="center">TEW-Bots</h1>

<p align="center">
  <strong>Turn an old PC or laptop into an Ubuntu home server and run always-on AI bots on the Claude subscription you already have, or with your own API key.</strong>
</p>

<p align="center">
  <a href="https://github.com/theempirewithin/tew-bots/subscription"><strong>👀 Watch → Releases</strong></a> to join the waitlist ·
  <a href="https://github.com/theempirewithin/tew-bots/stargazers"><strong>⭐ Star</strong></a> to follow progress
</p>

---

> **Early access:** TEW-Bots is getting ready for its first public release, and this repository is where it will live.
> To hear when v1 is out, click **⭐ Star** and **👀 Watch → Custom → Releases** at the top right.

---

## Why

Got an old laptop or desktop in a drawer? Instead of letting it collect dust or paying for another cloud server, turn it into an Ubuntu home server that runs your own AI bots around the clock.

You install it once. After that it runs as a background service, comes back after a reboot, and you can reach it privately from your phone or main PC. No juggling `localhost` in a terminal.

## What's coming

- An installer that sets up Node, Claude Code, Chromium and a `systemd` service (`Restart=always`) on Ubuntu Server in one step.
- Bots run through `claude -p` on your own Claude account. If you prefer, they can use Anthropic, OpenAI or Gemini API keys, or a local OpenAI-compatible server such as Ollama or LM Studio. Your Claude subscription is for personal use under Anthropic's [Consumer Terms](https://www.anthropic.com/legal/consumer-terms). For business use, run the bots with an API key.
- Private access over Tailscale, so you reach the web UI from your devices without opening ports on your router.
- Named bots with 3D avatars, chats that persist, scheduled runs and a separate browser profile for each bot.
- An Inbox where bots leave results and proposed actions for you to approve, edit or reject.
- Plugin tools with permissions per bot, and optional Telegram alerts.

## Status

The core framework, scheduler, per-bot browser profiles, Inbox, plugins and the Ubuntu installer are built in a private repository.

Next: the first live test on a dedicated Ubuntu Server PC, cleanup for the public release, and v1 here, together with the YouTube series about the build.

To follow along, star the repository and watch it for releases.

## License

TEW-Bots is licensed under the [GNU Affero General Public License v3.0 (AGPL-3.0)](LICENSE). You can use it for free, including for internal business automation.
To build, distribute or host a proprietary or commercial product on top of TEW-Bots without the AGPL-3.0 copyleft obligations, you need a separate commercial license from **The Empire Within**.

Copyright © 2026 The Empire Within
