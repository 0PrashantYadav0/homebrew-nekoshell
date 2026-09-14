# homebrew-nekoshell

The Homebrew tap for [nekoshell](https://github.com/0PrashantYadav0/nekoshell), a Catppuccin terminal rig for macOS.

```bash
brew tap 0PrashantYadav0/nekoshell
brew install nekoshell
nekoshell install
```

`brew upgrade nekoshell` moves to the next release; nekoshell records the tap's `opt` path as its root, so the links in your home survive the upgrade. `brew uninstall nekoshell` removes the tree; run `nekoshell uninstall` first if you want your shell put back the way it was.

`brew install --HEAD nekoshell` installs the main branch.

## How this tap is updated

`Formula/nekoshell.rb` is written by the release workflow in the nekoshell repository, from `packaging/homebrew/nekoshell.rb.tmpl` there. Do not edit it here; change the template and cut a release.
