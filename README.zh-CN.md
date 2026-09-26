# kenshi-ui-localization

[English](README.md) · [繁體中文](README.zh-TW.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md)

Kenshi 有些 MOD 会自带 DLL（RE_Kenshi 插件），把界面文字放在 MOD 自己的 `Localization/*.json` 里。
这种文字**无法用另一个 MOD 覆盖**，因为 DLL 固定从原始 MOD 目录下的路径读取。
本仓库放这类界面文字的机翻语言文件，供手动安装。

语言文件由 Google 页面翻译生成，变量（`%s`、`%d`、`{destination}`）与换行都与原文一致。

## 目前收录

| 原始 MOD | 创意工坊 | 语言文件 |
|---|---|---|
| The Mercenarie ( RE_Kenshi )<br>（模组列表中的名称：`Guild Escort Contracts`） | [3798671709](https://steamcommunity.com/sharedfiles/filedetails/?id=3798671709) | [`zh_tw.json`](mods/3798671709-the-mercenarie/zh_tw.json) · [`zh_cn.json`](mods/3798671709-the-mercenarie/zh_cn.json) · [`ja.json`](mods/3798671709-the-mercenarie/ja.json) |

## 安装方式

1. 下载你要的语言文件（点上表的文件名 → 右上角 **Download raw file**）。
2. 放进原始 MOD 的 `Localization` 目录：
   - **订阅创意工坊安装**：`…\steamapps\workshop\content\233860\3798671709\Localization\`
   - **手动安装**：`…\Kenshi\mods\Guild Escort Contracts\Localization\`

   该目录里原本应该已有 `en.json`、`fr.json`、`pl.json`、`ru.json`。把下载的文件放在旁边即可，**不要改文件名**。
3. 进游戏，在该 MOD 的设置画面把语言改成对应选项。语言列表是依目录里的文件生成的，所以放对就会出现。

## 注意

- **原始 MOD 更新后，Steam 会还原创意工坊目录，放进去的文件可能被删掉。**更新后再放一次即可。
- 语言文件的键必须与 `en.json` 一致。原作者改版新增字符串时，缺少的键会退回英文。
- 这些文件除了翻译后的字符串以外，不包含原始 MOD 的任何内容。

## 相关

装备、物品、对话、开局设定等“游戏本体读取”的文字，另外以创意工坊的汉化 MOD 提供：
<https://steamcommunity.com/profiles/76561198798313334/myworkshopfiles/>
