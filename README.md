# shiloong/homebrew-tap

Homebrew tap for [ANOLISA](https://github.com/alibaba/anolisa) components.

## tokenless

LLM Token Optimization Toolkit — schema/response compression, TOON encoding, and command rewriting.

### Install

```bash
brew tap shiloong/tap
brew install tokenless
```

### Post-install

```bash
# Claude Code
$(brew --prefix)/share/anolisa/adapters/tokenless/claude-code/scripts/install.sh

# Copilot Shell (cosh) — auto-discovered from:
# $(brew --prefix)/share/anolisa/extensions/tokenless/
```

### What is installed

| Type | Path |
|------|------|
| Main binary | $(brew --prefix)/bin/tokenless |
| Helpers | $(brew --prefix)/bin/rtk, $(brew --prefix)/bin/toon |
| Adapter resources | $(brew --prefix)/share/anolisa/adapters/tokenless/ |
| Cosh extension | $(brew --prefix)/share/anolisa/extensions/tokenless/ |
| Documentation | $(brew --prefix)/share/doc/tokenless/ |

### Requirements

- macOS (Apple Silicon or Intel)
- Xcode Command Line Tools
- Homebrew installs build dependencies automatically (Rust, Node.js, Python 3, jq)
