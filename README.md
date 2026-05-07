# Nord Blue

An Obsidian theme based on [Obsidian Nord](https://github.com/insanum/obsidian_nord) with blue/cyan color overrides inspired by Tokyo Night.

## What's different from Obsidian Nord

- Headings use a blue gradient (#7aa2f7, #7dcfff, #89b4fa, #74c7ec)
- Links and accents are blue/cyan instead of orange/red
- Text selection is light yellow instead of red
- Cursor line highlight is subtle blue
- Bold is bright white, italic is blue
- Tags are cyan

## Install

Symlink into your vault's themes directory (recommended - single source of truth):

```sh
ln -s /path/to/obsidian-nord-blue "/path/to/vault/.obsidian/themes/Nord Blue"
```

Or clone directly:

```sh
cd /path/to/vault/.obsidian/themes
git clone https://github.com/jritsema/obsidian-nord-blue.git "Nord Blue"
```

Then in Obsidian: Settings > Appearance > Themes > select "Nord Blue".

**Note:** This theme requires translucency to be disabled (Settings > Appearance > Translucent window = off).

## Reloading after changes

Obsidian caches theme CSS in memory. After editing `theme.css`, do one of:

- Restart Obsidian, or
- Switch to another theme and back (Settings > Appearance > Themes)

Cmd+R alone may not pick up changes through symlinks.

## Update

```sh
cd /path/to/vault/.obsidian/themes/Nord\ Blue
git pull
```

## Credits

- Base theme: [Obsidian Nord](https://github.com/insanum/obsidian-nord) by insanum
- Color palette inspired by [Tokyo Night](https://github.com/enkia/tokyo-night-vscode-theme)
