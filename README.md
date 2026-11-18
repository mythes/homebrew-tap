# Homebrew tap for agents-farm

```bash
brew install mythes/tap/agents-farm
```

This installs [agents-farm](https://github.com/mythes/agents-farm), a terminal dashboard for Claude Code agents, into its own Python environment. You get the commands `agents-farm` and `af`. Then run `af --demo` to try it.

- Update: `brew upgrade agents-farm`
- Remove: `brew uninstall agents-farm`

This tap can hold more apps: each one is a file in `Formula/` and installs with `brew install mythes/tap/<name>`. The agents-farm formula is `Formula/agents-farm.rb`. When agents-farm has a new release, change `url` and `sha256` (and the `resource` blocks if the dependencies changed; `brew update-python-resources mythes/tap/agents-farm` does that).
