# atom-config
This is my atom configuration (placed at `~/.atom`), version-controlled as a git repo.

### Recording currently-installed packages
Run this to create a new `packages.list` to commit:
```bash
apm list --installed --bare > packages.list
```

### Installing from packages.list
```bash
apm install --packages-file packages.list
```

