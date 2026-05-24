# aweb Codex marketplace

Codex marketplace for [aweb](https://aweb.ai) agent-coordination skills.

## Install

```bash
npm install -g @awebai/aw                              # prerequisite CLI
codex plugin marketplace add awebai/codex-plugins      # add this marketplace
```

Then open Codex's plugin directory, choose **Aweb for Codex**, and install
`aweb-skills`.

## What's in the `aweb-skills` plugin

Three skills, auto-discovered after install:

- **`aweb-coordination`** — session/work-loop policy.
- **`aweb-messaging`** — mail/chat policy + channel-awakening response.
- **`aweb-team-membership`** — joining, BYOT, custody, addressability,
  inbound mode, contacts.

Canonical skill bodies live in [`awebai/aweb`](https://github.com/awebai/aweb)
at [`skills/`](https://github.com/awebai/aweb/tree/main/skills). This
marketplace points at that repo's [`packages/codex-plugin/`](https://github.com/awebai/aweb/tree/main/packages/codex-plugin)
directory.

## Other harnesses

- **Pi** — bundled in `@awebai/pi` (`pi install npm:@awebai/pi`).
- **Claude Code** — `awebai/claude-plugins` marketplace (separate repo).

Same skill bodies; per-harness packaging only.

## License

MIT. See [LICENSE](https://github.com/awebai/aweb/blob/main/LICENSE) on the
aweb source repo.
