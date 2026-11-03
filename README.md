# zeshicast-gh

A [zeshicast](https://github.com/zeshi09/zeshicast) extension: your open
pull requests, review requests and assigned issues on GitHub.

Type `gh` in the palette; `gh <words>` filters by title, repository or
number, Enter opens the item in the browser. "GitHub: refresh" fetches the
lists (the palette must answer within 400 ms, so searching reads a cache
in `~/.cache/zeshicast-gh/`).

Needs [`gh`](https://cli.github.com/) logged in (`gh auth login`) and `jq`.

Capabilities: `shell` (runs `gh`), `open_url`.

```sh
zeshicast --extension-install zeshi09.gh
```
