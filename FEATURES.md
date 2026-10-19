# Built-in features for hearthside-os

Purpose: household planning

1. **prepare a creative project** — run hearthside-os-workspace. It creates ~/Documents/hearthside-os-workspace/ with Briefs, Working Files, Exports folders.
2. **plan a production session** — run hearthside-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/hearthside-os-session-plans/.
3. **check project and export readiness** — run hearthside-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/hearthside-os-workspace features/hearthside-os-plan features/hearthside-os-check "$HOME/.local/bin/"
