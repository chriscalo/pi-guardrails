---
"@aliou/pi-guardrails": minor
---

Improve settings UX with guided policy creation and top-level examples tab.

- Add a real wizard flow for creating a new policy in settings (name, protection, patterns, review), then open the policy editor.
- Move policy examples into a dedicated top-level `Examples` tab using `extraTabs`.
- Ask target scope each time an example is applied; do not persist last selected scope.
- Upgrade `@aliou/pi-utils-settings` to `^0.8.0` to use `extraTabs` and combined settings theme support.
- Keep pattern editor compact while preserving `Ctrl+R` regex toggle in form mode.
