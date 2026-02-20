# Homebrew Tap for Verge CLI

Official [Homebrew](https://brew.sh) tap for [Verge CLI (`vrg`)](https://github.com/verge-io/vrg) — the command-line interface for [VergeOS](https://verge.io).

## Install

```bash
brew install verge-io/tap/vrg
```

## Upgrade

```bash
brew upgrade vrg
```

## Verify

```bash
vrg --version
```

## Shell Completion

```bash
vrg --install-completion
```

> **macOS zsh note:** If you see `compinit: insecure directories` after installing completions, run:
> ```bash
> chmod 755 /opt/homebrew/share/zsh /opt/homebrew/share/zsh/site-functions
> ```

## Uninstall

```bash
brew uninstall vrg
brew untap verge-io/tap
```

## Links

- [Verge CLI](https://github.com/verge-io/vrg) — Source, documentation, and issue tracker
- [PyPI](https://pypi.org/project/vrg/) — Also available via `pip install vrg`
- [VergeOS](https://verge.io) — Ultraconverged infrastructure platform
