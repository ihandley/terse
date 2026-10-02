# The canonical install block

One install story. `README.md` must say this and nothing else. Change it here first, then propagate.

Terse is not in Claude Code's official marketplace. Install it from this repo. The two routes below are exclusive.

## Claude Code: the plugin

```bash
claude plugin marketplace add ihandley/terse
claude plugin install terse@ihandley
```

Or, from inside a session:

```
/plugin marketplace add ihandley/terse
/plugin install terse@ihandley
```

The plugin is a managed, read-only bundle. Updates arrive when Claude Code updates the plugin.

## Cortex, Codex, and other agents: skills.sh

The plugin is Claude Code only. Everywhere else, skills.sh copies editable skill files. Cortex Code is agent `cortex`.

```bash
npx skills@latest add ihandley/terse --agent cortex
```

Omit `--agent` to choose the agents interactively:

```bash
npx skills@latest add ihandley/terse
```

Update by re-running the add command:

```bash
npx skills@latest update terse
```

## The two routes are exclusive

The plugin is a managed bundle you subscribe to. skills.sh writes files you own and edit. Installing both leaves the skill installed twice. Pick one.
