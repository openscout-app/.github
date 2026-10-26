<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/openscout-app/.github/main/profile/assets/scout-mesh-dark.png" />
    <img src="https://raw.githubusercontent.com/openscout-app/.github/main/profile/assets/scout-mesh-light.png" alt="Scout connects agents on your Mac, a Linux box, a cloud sandbox, a colleague's Mac, and a hosted Scout Chat room. Cursor asks you to approve a deploy." width="100%" />
  </picture>
</p>

<h3 align="center">All your agents, working as one team.</h3>

<p align="center">
  Scout gives every agent you run an address. Requests reach the right one,
  answers come back to whoever asked, and you're asked only when it's yours to decide.
</p>

<p align="center">
  <a href="https://github.com/openscout-app/scout"><img alt="Scout" src="https://img.shields.io/badge/explore-Scout-fff7ea?style=flat-square&labelColor=171a16" /></a>
  <a href="https://www.npmjs.com/package/@openscout/scout"><img alt="npm version" src="https://img.shields.io/npm/v/@openscout/scout?style=flat-square&label=npm&color=f7f4ea&labelColor=171a16" /></a>
  <a href="https://openscout.app"><img alt="openscout.app" src="https://img.shields.io/badge/home-openscout.app-dde6d8?style=flat-square&labelColor=171a16" /></a>
</p>

---

## Start with Scout

[`openscout-app/scout`](https://github.com/openscout-app/scout) is the open
core: the `scout` CLI and MCP server, the local runtime, the protocol, and the
harness adapters. It is Apache 2.0.

```bash
bun add -g @openscout/scout
scout setup
scout ask --project . --harness codex "Review my changes."
```

Add your other machines when you need them. Agents on a Linux box, a cloud
sandbox, or a teammate's machine pick up work the same way.

## Bring the agents you already use

| Your tool | Scout integration |
| --- | --- |
| Claude Code | [Commands and channel](https://github.com/openscout-app/claude-scout) |
| Codex | [MCP tools and coordination skill](https://github.com/openscout-app/codex-scout) |
| Cursor | [Editor MCP configuration](https://github.com/openscout-app/cursor-scout) |
| Grok Bot | [Hosted connector](https://github.com/openscout-app/grok-scout) |
| Hermes | [Conversation and tool bridge](https://github.com/openscout-app/hermes-scout) |
| herdr | [Terminal pane actions and feed](https://github.com/openscout-app/herdr-scout) |
| pi | [Native Scout tools](https://github.com/openscout-app/pi-scout) |

## How Scout works

| Principle | In practice |
| --- | --- |
| **Local first** | The runtime and its records stay on machines you own. |
| **Explicit routing** | Targets and channels are structured data, not guesses hidden in message text. |
| **Durable work** | Asks, replies, and handoffs outlive the session that started them. |
| **Observed transcripts** | Harness history stays source material. Scout does not import it as its own chat. |
| **Honest mesh** | Mesh means reachability and coordination, not consensus or exactly-once delivery. |

Scout is built for high-trust local developer use: you, your machines, and
the people you choose to share with. It does not claim enterprise or compliance
readiness.

## Find your way in

- [Install Scout](https://github.com/openscout-app/scout#install-and-first-run)
- [See what lives where](https://github.com/openscout-app/scout#what-lives-where)
- [Read the docs](https://openscout.app/docs)
- [Contribute](https://github.com/openscout-app/scout/blob/main/CONTRIBUTING.md)
- [Get support](https://github.com/openscout-app/scout/blob/main/SUPPORT.md)
- [Report a security issue](https://github.com/openscout-app/scout/security/policy)

<p align="center"><sub>Built for operators who want agents to work together without giving up the controls.</sub></p>
