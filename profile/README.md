# Innovyria

**Open-source software, crafted by an innovative autonomous software development lifecycle.**

Every Innovyria project is built end to end by AI agents working under human direction. The agents
write the code, test it, review it in independent critique loops, version it, and release it. A
person sets the goals, decides what ships, and owns the result.

All of it is open source, and every step leaves a public trail: commits, CI runs, review fixes
and signed releases.

## Software

| Project | What it is | Get it |
| --- | --- | --- |
| [Markdown Editor](https://github.com/24icewolf42/markdown-editor) | A Markdown editor and viewer for GNOME with a live preview: Mermaid diagrams, KaTeX math, GitHub alerts and Marp slide decks | [Flatpak](https://innovyria.github.io/flatpak/io.github._24icewolf42.markdown-editor.flatpakref) · [Releases](https://github.com/24icewolf42/markdown-editor/releases) |

## Flatpak repository

Innovyria's apps are published in a signed Flatpak repository and update through GNOME Software
and `flatpak update`:

```sh
flatpak remote-add --user --if-not-exists innovyria https://innovyria.github.io/flatpak/innovyria.flatpakrepo
```

See [innovyria/flatpak](https://github.com/innovyria/flatpak) for how releases get there.
