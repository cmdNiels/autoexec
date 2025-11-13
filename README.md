# CS2 Autoexec

This repository contains autoexec files for Counter-Strike 2.

## Installation Instructions

1. **Clone this repository** directly into your CS2 game directory:
   ```bash
	git init
	git remote add origin https://github.com/cmdNiels/autoexec
	git fetch --depth 1
	git reset --hard origin/master
   ```

2. **Launch CS2** and the autoexec will be automatically loaded.

## Update Instructions

1. **Pull the latest changes** from your CS2 game directory:
   ```bash
   git pull origin master --depth 1 --force
   ```
   The `--force` flag ensures that any local changes are overwritten automatically.

2. **Replace existing files** automatically without prompts.

3. **Launch CS2** to ensure the updated autoexec files are loaded.

## Directory Structure

This should be cloned into the CS2 game directory under:
```
Counter-Strike Global Offensive/game/csgo/
```

You can find this by right-clicking the game in your Steam library and under "Manage" click "Browse local files".

## Notes

- Make sure to backup any existing configuration files before installation
- The autoexec files will be automatically executed when CS2 starts
- If you need to modify settings, edit the configuration files and restart the game

## Troubleshooting

If the autoexec doesn't load:
1. Verify the files are in the correct directory
2. Check that CS2 has proper file permissions
3. Restart CS2 completely
