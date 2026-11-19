# Peanut

A fast, light IDE for macOS (Apple Silicon and Intel, macOS 11+): editor with LSP, Git review of agent worktrees, databases (MySQL, PostgreSQL, Redis, MongoDB, also inside Kubernetes).

## Install

Open Terminal and run:

```sh
curl -fsSL https://github.com/mikrahub/peanut-releases/releases/latest/download/install.sh | sh
```

It downloads the latest build, puts Peanut into Applications and starts it. No "Apple could not verify" dialog: that only appears for files downloaded in a browser.

After that Peanut updates itself: when a new version is out it shows a notice, **Install & Restart** downloads it, checks its signature and restarts.

### Manual download

[Peanut.dmg](https://github.com/mikrahub/peanut-releases/releases/latest/download/Peanut.dmg) (latest). macOS blocks apps downloaded in a browser that aren't notarized by Apple; to open it once:

- System Settings → Privacy & Security → **Open Anyway**, or
- in Terminal: `xattr -dr com.apple.quarantine /Applications/Peanut.app`

## Releases

All versions: [Releases](https://github.com/mikrahub/peanut-releases/releases). The source code lives in a private repository.
