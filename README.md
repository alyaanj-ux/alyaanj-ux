## Hi, I'm Alyaan

I build desktop tools for Windows, mostly to scratch my own itches — and one
instrument for telling whether a result is real.

### Projects

| | What it is | Built with |
|---|---|---|
| **[nullbench](https://github.com/alyaanj-ux/nullbench)** | A domain-agnostic instrument that measures whether a claimed result is distinguishable from luck. Calibrated against markets, weather, and synthetic noise — data where the answer is already known — so it demonstrably reads correctly in *both* directions through one code path. | Python |
| **[sentry](https://github.com/alyaanj-ux/sentry)** | A local heuristic file scanner for Windows. Layered static detection — known-bad hashes, YARA, PE structure, suspicious API combinations, script obfuscation — that ranks files for review. It never moves or deletes anything on its own; quarantine is enforced behind a human verdict in code. | Python · 556 tests |
| **[vault](https://github.com/alyaanj-ux/vault)** | One library for every game you own — Steam, Epic, GOG, EA, Ubisoft, Battle.net, Game Pass, five emulators, and any folder you point at it. Each platform gets the launch path it actually needs, which is why the games start. | TypeScript · Electron |
| **[snapmaster](https://github.com/alyaanj-ux/snapmaster)** | Window snapping for Windows. Draw your own zone layouts, then throw windows into them with a hotkey. Layouts are stored as fractions of the work area, so one drawn on a 1080p monitor lands correctly on a 4K one. | JavaScript · Electron · Win32 |
| **[claude-usage-overlay](https://github.com/alyaanj-ux/claude-usage-overlay)** | A small always-on-top widget showing live Claude usage. Three versions that differ only in *when* the overlay is on screen — the interesting problem turned out to be "is the user working right now?" | Python · Tkinter |

### How I try to write things

Every repo above has a **known limitations** section, and they're real ones —
what the tool can't do, what wasn't verified on hardware I don't own, and which
approach I picked over the "proper" one because the proper one was less reliable.
A tool that overstates itself is worse than a smaller tool that doesn't.
