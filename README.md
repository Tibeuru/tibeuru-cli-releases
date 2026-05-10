# Tibeuru CLI — releases

Public installer downloads for **tibeuru.exe** — the Dart console binary that wraps `api.tibeuru.com` + `mcp.tibeuru.com`.

**Source code lives in a private repo** — this repo exists only to host downloads.

## Install

### One-liner (recommended)
```powershell
irm https://studio.tibeuru.com/install.ps1 | iex
```
Drops `tibeuru.exe` onto your PATH and verifies the install with `tibeuru --version`.

### Direct download
[Grab the latest `tibeuru.exe`](https://github.com/Tibeuru/tibeuru-cli-releases/releases/latest) and put it on your PATH yourself.

## What it does

`tibeuru.exe` is a single native binary (no runtime dependency) that talks to:
- `api.tibeuru.com` for Tibeuru account + product API
- `mcp.tibeuru.com` for the Tibeuru MCP servers (the same servers Claude Desktop and Claude Code can use via Tibeuru Connect)

Auth is a `tbk_*` key saved at `%APPDATA%\Tibeuru CLI\config.json` after `tibeuru login`.

Run `tibeuru` with no args for the help banner, or `tibeuru --help` for the subcommand list.

## License

See [tibeuru.com](https://tibeuru.com) — proprietary.
