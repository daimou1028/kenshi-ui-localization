# kenshi-ui-localization

[English](README.md) · [繁體中文](README.zh-TW.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md)

Some Kenshi mods ship their own DLL (RE_Kenshi plugins) and keep their interface text in the mod's own
`Localization/*.json`. **A separate workshop mod cannot override that text**, because the DLL reads it from a
path fixed inside the original mod's folder. This repository holds machine-translated language files for that
kind of text, to be installed by hand.

The files are produced with Google page translation. Placeholders (`%s`, `%d`, `{destination}`) and line
breaks are kept exactly as in the original.

## Included

| Original mod | Workshop | Files |
|---|---|---|
| The Mercenarie ( RE_Kenshi )<br>(name in the mod list: `Guild Escort Contracts`) | [3798671709](https://steamcommunity.com/sharedfiles/filedetails/?id=3798671709) | [`zh_tw.json`](mods/3798671709-the-mercenarie/zh_tw.json) · [`zh_cn.json`](mods/3798671709-the-mercenarie/zh_cn.json) · [`ja.json`](mods/3798671709-the-mercenarie/ja.json) |

## How to install

1. Download the file you want (open it above, then **Download raw file** at the top right).
2. Put it in the original mod's `Localization` folder:
   - **Subscribed on the workshop**: `…\steamapps\workshop\content\233860\3798671709\Localization\`
   - **Installed by hand**: `…\Kenshi\mods\Guild Escort Contracts\Localization\`

   That folder should already contain `en.json`, `fr.json`, `pl.json`, `ru.json`. Put the new file next to them
   and **do not rename it**.
3. Start the game and switch the language in the mod's own settings screen. The list is built from the files
   present in that folder, so the new language appears once the file is there.

## Notes

- **Steam restores the workshop folder when the original mod updates, which can delete the file.** Put it back after an update.
- The keys must match `en.json`. If the author adds new strings, the missing keys fall back to English.
- These files contain nothing from the original mod except the translated strings.

## Related

Text the game itself reads (equipment, items, dialogue, start options) is translated as ordinary workshop mods:
<https://steamcommunity.com/profiles/76561198798313334/myworkshopfiles/>
