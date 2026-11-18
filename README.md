# Homebrew tap for agents-farm

```bash
brew install mythes/tap/agents-farm
```

This installs [agents-farm](https://github.com/mythes/agents-farm), a terminal dashboard for Claude Code agents, into its own Python environment. Then run `agents-farm --demo` to try it.

- Update: `brew upgrade agents-farm`
- Remove: `brew uninstall agents-farm`

The formula is `Formula/agents-farm.rb`. When agents-farm has a new release, change `url` and `sha256` (and the `resource` blocks if the dependencies changed; `brew update-python-resources mythes/tap/agents-farm` does that).
