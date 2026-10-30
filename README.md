## RuneLite plugins

I build RuneLite plugins for clearer menus, useful bank views and a more personal interface. Each plugin works on its own, with optional integrations where they help.

| Plugin | What it does |
| --- | --- |
| **[Improved Banking](https://github.com/wukuna/improved-banking)** · Beta | Search Wiki activities and item uses, preview phase-specific gear and inventories, save editable presets, and customize bank markers, controls and screenshots. |
| **[Improved Looting](https://github.com/wukuna/improved-looting)** · Beta | Ground loot cards or labels with Native / OSRS themes, custom backgrounds, seven price tiers, loot beams, despawn timers, quick hiding and a nearby loot browser. |
| **[Improved Right-Clicks](https://github.com/wukuna/improved-right-clicks)** | Menu cleanup, misclick protection, item rules, action colors, loot icons, optional player badges and an OSRS menu theme. |
| **[Interface Layout](https://github.com/wukuna/interface-layout)** | Move orbs, the compass and menu tabs; build custom bars and control minimap visibility. Includes an optional Beta equipment sidebar with compact stats and spellbook information. |
| **[Improved Chat and Overlays](https://github.com/wukuna/improved-chat-and-overlays)** | Separate chat overlays with filters, fonts, colors and alerts, plus native chat resizing, collapse controls and dialogue styling. |

Install through RuneLite's **Plugin Hub** using the names above. Each repository explains its settings, compatibility and known limitations. Banking and Looting are Beta plugins; other experimental features are marked individually.

### Latest updates

As of **30 October 2026**, all five plugins have entries in the Plugin Hub. The latest Right-Clicks and Interface Layout updates have merged. Further updates are still under review:

- **[Improved Banking #19695](https://github.com/runelite/plugin-hub/pull/19695):** editable preset positions, bank controls, item alternatives and separate preset display switches.
- **[Improved Looting #19769](https://github.com/runelite/plugin-hub/pull/19769):** easier-to-find theme selection and a more compact settings panel.

Repository documentation can describe newer work than the installed Hub build. The linked PRs show its current review status. A local **TEST** build is separate from the normal Hub release.

### Using them together

Improved Looting can share ground-item icons with Improved Right-Clicks through **Connect menu icons**. Bank Tags and Bank Tag Layouts remain separate companions to Improved Banking; existing saved tag layouts are retained.

Automatic icon sharing from the separate **Loot Filters** plugin still depends on [its pending provider update](https://github.com/riktenx/loot-filters/pull/219). Regular released Loot Filters does not yet provide it.

## Report an issue

Open the relevant repository's **Issues** page and check for an existing report first. Include:

- Steps to reproduce, plus expected and actual behavior.
- Your RuneLite and plugin versions, and whether you use the normal Hub or a TEST build.
- Relevant settings, including Beta or experimental options and overlapping plugins.
- Screenshots or error messages, with private information removed.

Check the repository's compatibility notes when troubleshooting. RuneLite handles declared plugin conflicts, but overlapping settings can still need adjustment.

You can also contact me on **Discord: wukuna_**.
