# claude-plugins

Claude Code plugin marketplace for my plugins. Each plugin lives in its own
repository; this one only lists them.

```
/plugin marketplace add juliantrude/claude-plugins
/plugin install <plugin>@juliantrude
```

| Plugin | What it does |
|---|---|
| [hustlebot](https://github.com/juliantrude/hustlebot) | Cross-session goal loop that keeps working across subscription limits |

To add a plugin, add an entry with a `github` source to
`.claude-plugin/marketplace.json`.
