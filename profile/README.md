<div align="center">

# viberfasend

**Vibe-coded side projects by [Andreas Sander](https://andi1984.dev).**

Ideas that turned into working software with an AI pair programmer in the loop.
Local-first by habit, shipped when they're useful, polished when they're fun.

</div>

---

## What lives here

Everything in this org started as a "what if…" and was built largely by talking to a coding agent. That means:

- **Fast from idea to something runnable.** Most projects went from empty repo to daily use in days, not months.
- **Real engineering underneath.** Tests, CI, ADRs, and docs where they earn their keep. Vibe-coded, not throwaway.
- **Local-first, no accounts.** Data stays on your device unless you explicitly opt into sync.
- **Scratching my own itches.** If a project is useful to you too, great. If not, that's fine as well.

## Projects

| Project | What it is | Stack | Try it |
| --- | --- | --- | --- |
| [**Ferrico**](https://github.com/viberfasend/ferrico_dot_app) | Fast, local-first bookmark manager for macOS, Linux, and Windows. Folders, tags, fuzzy search, duplicate and dead-link detection, optional Google Drive sync, browser extension, read-only Android companion. | Tauri 2 · Rust · React 19 · SQLite | [Website](https://viberfasend.github.io/ferrico_dot_app/) |
| [**Kann ich lüften?**](https://github.com/viberfasend/kann-ich-lueften) | Should I open the windows right now? Compares *absolute* humidity inside and outside, checks for condensation on cold surfaces, and suggests how long to air the room. Installable PWA, works offline. German UI. | TypeScript · Vite · Vitest · Open-Meteo | [Open app](https://viberfasend.github.io/kann-ich-lueften/) |
| [**Racing game**](https://github.com/viberfasend/love2dgame) | 2D racing game with neuroevolution AI opponents. Started in Love2D/Lua, ported to Rust on Bevy. The pure simulation lives in its own engine-free, unit-tested crate. | Rust · Bevy 0.16 · Lua (legacy) | `cargo run` |
| **Cadence** 🔒 | Native Android and desktop todo app. Importance first, due date breaks ties, with recurrence that understands both calendar rules and "n days after completion". Fully usable offline and signed out; sync is one optional sign-in. | Kotlin · Compose Multiplatform · SQLDelight | private |
| **Inoswipe** 🔒 | Swipe through your Inoreader backlog two articles at a time: keep one, mark the other read. Inbox zero, but fun. Tokens never reach the browser thanks to a small Hono backend. | React 19 · Zustand · Hono · Node 24 | private |

🔒 = private for now. Might open up once they've settled.

## How these get built

The workflow is roughly the same across repos:

1. Describe the thing. Argue with the agent about the design until it's sane.
2. Let it write the boring parts, review the interesting ones.
3. Tests and CI from the first commit, so the next vibe session doesn't break the last one.
4. Write down decisions (ADRs) so future-me and future-agent know *why*.

Most repos carry a `CLAUDE.md` or similar agent guide that explains the architecture and commands. That file is usually the best place to start reading.

## Contributing

Issues and pull requests are welcome, but expectations should match the label on the box: these are hobby projects, maintained in evenings and weekends. Bug reports with reproduction steps get looked at. Feature ideas are read with interest and implemented on vibes.

## Elsewhere

- Blog and everything non-vibe: [andi1984.dev](https://andi1984.dev)
- Main GitHub account: [@andi1984](https://github.com/andi1984)

<div align="center">
<sub>Built with curiosity, coffee, and a very patient language model.</sub>
</div>
