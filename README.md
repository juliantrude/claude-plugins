# claude-plugins

Claude Code plugin marketplace for my plugins. Each plugin lives in its own
repository; this one only lists them.

```sh
claude plugin marketplace add juliantrude/claude-plugins
claude plugin install <plugin>@juliantrude
```

Inside a Claude Code session, the same works as `/plugin marketplace add …` and
`/plugin install …`.

| Plugin | What it does |
|---|---|
| [admiralty](https://github.com/juliantrude/admiralty) | Coaches Stellaris players from their save files |
| [ariadne](https://github.com/juliantrude/ariadne) | Lerntutor, der den Weg kennt und ihn nicht verrät |
| [hustlebot](https://github.com/juliantrude/hustlebot) | Cross-session goal loop that keeps working across subscription limits |

Some plugins need an extra step after the install, such as a first build. The
README of each plugin has its full setup.

To update everything later:

```sh
claude plugin marketplace update juliantrude
claude plugin update <plugin>@juliantrude
```

To add a plugin, add an entry with a `github` source to
`.claude-plugin/marketplace.json`.
