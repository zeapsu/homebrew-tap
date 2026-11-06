# zeapsu/homebrew-tap

Homebrew formulae for [Delta](https://github.com/zeapsu/Delta), a self-hosted personal finance dashboard with an MCP server for your agent.

```bash
brew install zeapsu/tap/delta
brew services start delta
```

Then open http://127.0.0.1:3000. Guide: [Install with Homebrew](https://zeapsu.github.io/Delta/docs/homebrew).

The formula's source lives in the Delta repo under `homebrew/`. `.github/workflows/bump.yml` moves it to each new Delta release, after building and testing it on macOS.
