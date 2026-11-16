# Web-tree Homebrew tap

```sh
brew install web-tree/tap/runspore
spore --version
```

| Formula | Installs |
| --- | --- |
| `runspore` | The [`spore`](https://github.com/Web-tree/runspore) CLI: durable workflows from your terminal. macOS and Linux, arm64 and x86_64. |

The formula uses the prebuilt release archives. `scripts/update-runspore.sh` writes it
from a release's `SHA256SUMS` only after checking the runspore release key's signature,
the same check `install.sh` makes. A scheduled workflow regenerates it every six hours
and on `repository_dispatch` (`runspore-release`), then installs and tests it on macOS
and Linux.

Upgrade with `brew upgrade runspore`.
