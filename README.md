# SalesPros Homebrew Tap

Homebrew formulae for [SalesPros](https://salespros.tools) tools.

## Install the Companion

```sh
brew install salespros-tools/tap/salespros
```

This installs the `salespros` binary — the SalesPros Companion: a local Apex
language server for the Chrome extension and an MCP server + CLI agent channel
for your SalesPros library. macOS (Apple silicon & Intel) and Linux x64.

Upgrade with `brew upgrade salespros-tools/tap/salespros`.

Prefer a script? `curl -fsSL https://salespros.tools/install.sh | sh`.

Docs for your AI assistant: <https://salespros.tools/llms/companion-cli.md>

---

`Formula/salespros.rb` is generated on each release by
`apps/companion/scripts/render-brew-formula.sh` in the (private) SalesPros
monorepo — edits here are overwritten.
