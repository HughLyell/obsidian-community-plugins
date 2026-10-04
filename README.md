# Obsidian Setup

My [Obsidian](https://obsidian.md) vault configuration — community plugins, settings, and theme setup — published so it can be replicated.

## How to use

**Option 1 — Clone as your vault (easiest):**

```bash
git clone https://github.com/HughLyell/obsidian-setup.git MyVault
```

Then open `MyVault` as a vault in Obsidian. Plugins will load automatically.

**Option 2 — Copy into an existing vault:**

Copy the `.obsidian` folder into your vault root (replace/merge), then restart Obsidian.

## What's inside

- `.obsidian/community-plugins.json` — list of enabled community plugins
- `.obsidian/plugins/` — each plugin's code (`main.js`, `manifest.json`) and settings (`data.json`)
- `.obsidian/core-plugins.json`, `app.json`, `appearance.json` — core plugin, app, and appearance settings
- `.obsidian/plugins/obsidian-icon-folder/icons.json` — custom folder/note icons

## Notes

- `workspace.json` (window layout) and `plugins/agent-client/sessions/` (chat history) are intentionally excluded — they're device-specific/personal.
- All API keys have been blanked from plugin settings. If a plugin needs a key (e.g. **Voice** for OpenAI/ElevenLabs), you'll need to enter your own in its settings after installing.
