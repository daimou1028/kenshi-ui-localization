# kenshi-ui-localization

[English](README.md) · [繁體中文](README.zh-TW.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md)

Kenshi 有些 MOD 會自帶 DLL（RE_Kenshi 外掛），把介面文字放在 MOD 自己的 `Localization/*.json` 裡。
這種文字**無法用另一個 MOD 覆蓋**，因為 DLL 固定從原始 MOD 目錄下的路徑讀取。
本倉庫放這類介面文字的機翻語言檔，供手動安裝。

語言檔由 Google 頁面翻譯產生，變數（`%s`、`%d`、`{destination}`）與換行都與原文一致。

## 目前收錄

| 原始 MOD | 工作坊 | 語言檔 |
|---|---|---|
| The Mercenarie ( RE_Kenshi )<br>（模組清單中的名稱：`Guild Escort Contracts`） | [3798671709](https://steamcommunity.com/sharedfiles/filedetails/?id=3798671709) | [`zh_tw.json`](mods/3798671709-the-mercenarie/zh_tw.json) · [`zh_cn.json`](mods/3798671709-the-mercenarie/zh_cn.json) · [`ja.json`](mods/3798671709-the-mercenarie/ja.json) |

## 安裝方式

1. 下載你要的語言檔（點上表的檔名 → 右上角 **Download raw file**）。
2. 放進原始 MOD 的 `Localization` 目錄：
   - **訂閱工作坊安裝**：`…\steamapps\workshop\content\233860\3798671709\Localization\`
   - **手動安裝**：`…\Kenshi\mods\Guild Escort Contracts\Localization\`

   該目錄裡原本應該已有 `en.json`、`fr.json`、`pl.json`、`ru.json`。把下載的檔案放在旁邊即可，**不要改檔名**。
3. 進遊戲，在該 MOD 的設定畫面把語言改成對應選項。語言清單是依目錄裡的檔案產生的，所以放對就會出現。

## 注意

- **原始 MOD 更新後，Steam 會還原工作坊目錄，放進去的檔案可能被刪掉。**更新後再放一次即可。
- 語言檔的鍵必須與 `en.json` 一致。原作者改版新增字串時，缺少的鍵會退回英文。
- 這些檔案除了翻譯後的字串以外，不包含原始 MOD 的任何內容。

## 相關

裝備、物品、對話、開局設定等「遊戲本體讀取」的文字，另外以工作坊的漢化 MOD 提供：
<https://steamcommunity.com/profiles/76561198798313334/myworkshopfiles/>
