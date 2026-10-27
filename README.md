# PCAPNG Analyzer for Homebrew

A [Homebrew](https://brew.sh) tap for
[PCAPNG Analyzer](https://pcapnganalyzer.com): drop in a pcap or pcapng
capture and get a plain-English diagnosis, with the evidence. It runs on
your own computer and opens in your browser. Your captures stay on your
machine. For macOS (Apple silicon and Intel) and Linux (x64 and arm64).

```sh
brew install stumat1/pcapng-analyzer/pcapng-analyzer
```

Then run `pcapng-analyzer`. Your browser opens on it, signed in. Leave it
running while you use the app; press Ctrl+C to stop.

| | |
|---|---|
| Update | Stop the app, then `brew upgrade pcapng-analyzer` |
| Remove | `brew uninstall pcapng-analyzer` |
| Your data | macOS: `~/Library/Application Support/PCAPNG Analyzer`; Linux: `~/.local/share/pcapng-analyzer`. Kept when you update or remove the app |

Free to use; a [Pro license](https://pcapnganalyzer.com/pricing.html)
unlocks the rest. The formula is updated automatically for each release
of [pcapng-analyzer-desktop](https://github.com/stumat1/pcapng-analyzer-desktop).
PCAPNG Analyzer is commercial, source-available software: see the
[license agreement](https://pcapnganalyzer.com/license.html).

Support: support@stumatapps.com
