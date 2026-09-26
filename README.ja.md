# kenshi-ui-localization

[English](README.md) · [繁體中文](README.zh-TW.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md)

Kenshi の MOD には、自前の DLL（RE_Kenshi のプラグイン）を同梱し、画面の文字を MOD 自身の
`Localization/*.json` に持つ物が在ります。この文字は**別の MOD では差し替えられません**。DLL が
原版 MOD のフォルダの中の決まった道から読むためです。この repo は、その種の文字を機械翻訳した
言語 file を配り、手で入れてもらう為の物です。

file は Google の頁翻訳で作りました。差し込みの印（`%s`・`%d`・`{destination}`）と改行は原文のままです。

## 収録

| 原版 MOD | ワークショップ | 言語 file |
|---|---|---|
| The Mercenarie ( RE_Kenshi )<br>（MOD 一覧での名前: `Guild Escort Contracts`） | [3798671709](https://steamcommunity.com/sharedfiles/filedetails/?id=3798671709) | [`zh_tw.json`](mods/3798671709-the-mercenarie/zh_tw.json) · [`zh_cn.json`](mods/3798671709-the-mercenarie/zh_cn.json) · [`ja.json`](mods/3798671709-the-mercenarie/ja.json) |

## 入れ方

1. 欲しい file を落とす（上の表から開き、右上の **Download raw file**）。
2. 原版 MOD の `Localization` フォルダへ置く:
   - **ワークショップで購読**: `…\steamapps\workshop\content\233860\3798671709\Localization\`
   - **手で入れた場合**: `…\Kenshi\mods\Guild Escort Contracts\Localization\`

   そのフォルダには `en.json`・`fr.json`・`pl.json`・`ru.json` が在るはずです。その隣に置き、**名前は変えないで下さい**。
3. ゲームを起こし、その MOD の設定で言語を変えます。言語の一覧はフォルダの中の file から作られるので、置けば出ます。

## 断り

- **原版 MOD が更新されると、Steam がワークショップのフォルダを戻し、この file を消す事が在ります。**その時はもう一度 置いて下さい。
- 鍵は `en.json` と揃っている必要が在ります。作者が文字列を足した時、無い鍵は英語のまま出ます。
- この file には、訳した文字列以外、原版 MOD の物は入っていません。

## 関連

ゲーム本体が読む文字（装備・アイテム・台詞・開始時の設定）は、ふつうのワークショップの MOD として出しています:
<https://steamcommunity.com/profiles/76561198798313334/myworkshopfiles/>
