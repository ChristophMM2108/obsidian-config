# obsidian-config

My Obsidian settings, community plugins, theme and CSS snippets.

## Use in a new vault

```sh
git clone https://github.com/ChristophMM2108/obsidian-config.git <NewVault>/.obsidian
```

Then open the vault in Obsidian and trust the community plugins when prompted.

## Update

From inside a vault's `.obsidian/` folder:

```sh
git pull                           # get latest config
git add -A && git commit -m "..." && git push   # save changes
```

`workspace.json` and `graph.json` are ignored on purpose because they hold state that belongs to one vault.
