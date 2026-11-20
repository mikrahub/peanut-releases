# Peanut

A fast, light IDE for macOS (Apple Silicon and Intel, macOS 11+) and Linux (x86_64): editor with LSP, terminal, Git review of agent worktrees, databases (MySQL, PostgreSQL, Redis, MongoDB, also inside Kubernetes).

## Install

Open a terminal and run:

```sh
curl -fsSL https://github.com/mikrahub/peanut-releases/releases/latest/download/install.sh | sh
```

- **macOS:** puts Peanut into Applications and starts it. No "Apple could not verify" dialog (that only appears for files downloaded in a browser). After that Peanut updates itself: **Install & Restart** downloads the new version, checks its signature and restarts.
- **Linux (x86_64):** installs `~/.local/bin/peanut` and adds Peanut to your applications menu. Needs a desktop (GTK3, X11 or Wayland). Run the same command again to update; Peanut tells you when a new version is out.

### Manual download

- macOS: [Peanut.dmg](https://github.com/mikrahub/peanut-releases/releases/latest/download/Peanut.dmg). macOS blocks browser-downloaded apps that aren't notarized by Apple; to open it once: System Settings → Privacy & Security → **Open Anyway**, or `xattr -dr com.apple.quarantine /Applications/Peanut.app`.
- Linux: [peanut-linux-x86_64.tar.gz](https://github.com/mikrahub/peanut-releases/releases/latest/download/peanut-linux-x86_64.tar.gz) — unpack and run `./peanut`.

## Releases

All versions: [Releases](https://github.com/mikrahub/peanut-releases/releases). The source code lives in a private repository.
