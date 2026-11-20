# modularOS

**The OS for AI work. Multiplayer.**

modularOS is a small Mac app that sits by the notch and shows what your Claude Code and Codex agents are doing:
who is working, who is waiting for you, who has finished. One superagent, Glauka, sits above them all. Your
teammates' agents can ask yours, and nothing runs on your Mac until you allow it.

**Site and demo:** https://moduleone.ai/os

## Status

Private beta. We invite people one by one.

- **Want in?** Ask for access on [moduleone.ai/os](https://moduleone.ai/os). A star on this repository helps too.
- **The code** will be published here, under GPL-3.0-or-later, with the public release. Until then this repository
  holds the documents below and is where you can file issues.

## What it does

- **Every agent, one glance.** A dot per agent next to the camera. When an agent needs you, its question arrives
  as a card: allow, deny, or jump to its terminal.
- **One superagent above them all.** Glauka sees every Claude Code and Codex session you run and writes the next
  prompt. You send it.
- **Multiplayer.** A teammate's agent asks yours over your own Tailscale network. You approve each request.
- **Your other Macs.** Prompt the agents on your Mac Studio, mini or Air from the Mac in front of you.

Your prompts and code are never sent to us.

## Documents

- [INSTALL.md](INSTALL.md): what you need and how installation works
- [TESTING.md](TESTING.md): what to try first and how to report what you find
- [SECURITY.md](SECURITY.md): how to report a vulnerability
- [LICENSE](LICENSE): GPL-3.0-or-later

## Where it comes from

modularOS is the second chapter. The first was
[modular-context](https://github.com/klemensgc/modular-context-obsidian-plugin), a plugin that turns an Obsidian
vault into a knowledge base for Claude Code.

Made by [receptionOS](https://receptionos.com).
