# ATM10 8.2 — 臺灣繁體中文伺服器資源包

供私人 All the Mods 10（ATM10 8.2）／Minecraft 1.21.1／NeoForge 玩家使用的繁體中文資源包。

## 下載與使用

**最新版本 R7.2**：[下載 ATM10-8.2-TW-R7.2-SERVER-RESOURCEPACK-ATTRIBUTED.zip](./ATM10-8.2-TW-R7.2-SERVER-RESOURCEPACK-ATTRIBUTED.zip)

**上一版 R7.1**：[下載 R7.1](./ATM10-8.2-TW-R7.1-SERVER-RESOURCEPACK-ATTRIBUTED.zip)（保留供回復）。

**舊版備份 R7**：[原版繁中資源包](./ATM10-8.2-TW-R7-SERVER-RESOURCEPACK-ATTRIBUTED.zip)（保留供回復）。

伺服器透過 server.properties 的 resource-pack URL 和 resource-pack-sha1 提供加入時的下載提示。玩家仍須在個人遊戲「選項 → 語言」選擇繁體中文（台灣）（zh_tw）；伺服器無法強制改變個人語言設定。

此版本只包含可下載的資源包，不會幫玩家安裝 RadioFM、VaultPatcher 或任何 NeoForge 模組 JAR，也不包含私人 Minecraft 世界存檔。RadioFM 本身必須另外安裝經 ATM10 8.2 測試的相容版本，由私人伺服器 AutoModpack 引導程序提供；此公開 GitHub 只發布語言資源。

## 相容與範圍

- Minecraft 1.21.1／ATM10 8.2
- R7.2 在 R7.1 原有 654 份繁中語言檔基礎上，新增 RadioFM 1.3.0 繁體中文 44/44 個原始語言鍵（資源包新增一份 `zh_tw.json`），不影響舊模組書籍與字型
- R7.1 更正 Industrial Foregoing（工業先鋒）術語：Latex「乳膠」、Dry Rubber「乾橡膠」、Tiny Dry Rubber「小塊乾橡膠」，同步修正 Patchouli 手冊；遊戲配方不變
- 仍可能有未翻譯或硬編碼的簡體中文與英文；不保證 100% 覆蓋

## 授權與來源

主要翻譯基於 [chiba233/atm10-zh-cn](https://github.com/chiba233/atm10-zh-cn) vr26；原作者／整理者：Hoshino Yumeka（星野夢華），依 [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) 標示來源、非商業使用並以相同方式分享。此包包含臺灣詞彙調整、部分模組語言補充與書籍、字型改善。其他資源權利仍屬各作者。

ZIP 內包含 CREDITS_AND_LICENSES.txt 與 ATTRIBUTION_AND_CHANGES.txt，務必保留。此項目非官方 ATM10 發行版，也不代表遊戲或模組作者背書。

## 仍顯示簡中如何處理？

先在 Minecraft 選項中選擇繁體中文（台灣），再到多人遊戲伺服器項目選「伺服器資源包：提示／啟用」並接受下載；若部分模組文字仍是簡體，表示仍有未覆蓋內容或需要另外安裝 R7 客戶端補丁。

## 維護

更新 ZIP 後請重新計算 SHA-1 並更新 server.properties。應等玩家下線、完成備份後才安排必要的正式伺服器重啟。
