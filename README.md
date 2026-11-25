# SDPE Plugins

Slime Desktop Pet Editor(史萊姆桌寵編輯器)的官方插件。
Official plugins for Slime Desktop Pet Editor.

主程式 Main app:[SDPE - Slime Desktop Pet Editor](https://github.com/MaltoseSlime/SDPE---Slime-Desktop-Pet-Editor)

## 插件清單 Plugin list

<!-- plugin-list:start -->
| 插件 Plugin | 正式版 Stable | 測試版 Beta | 需要主程式 Requires app |
|---|---|---|---|
| **小遊戲擴充包** / Mini-Game Pack<br>`cards_color` | — | [1.0.0b](https://github.com/MaltoseSlime/SDPE-Plugins/releases/tag/cards_color-v1.0.0b) | 0.4.0b |
| **聊天** / Chat<br>`chat_symbolic` | — | [1.0.0b](https://github.com/MaltoseSlime/SDPE-Plugins/releases/tag/chat_symbolic-v1.0.0b) | 0.4.0b |
| **MIDI 播放** / MIDI Player<br>`midi_player` | — | [1.0.0b](https://github.com/MaltoseSlime/SDPE-Plugins/releases/tag/midi_player-v1.0.0b) | 0.4.0b |
<!-- plugin-list:end -->

## 插件說明 About the plugins

**聊天 / Chat**:跟桌寵用文字聊天(群組與 1v1)。桌寵用自己的回答台詞回應,可以教牠說法、糾正牠的理解;會照你的話去跳舞、睡覺、唱歌、找別隻桌寵玩。全部離線運作。每隻桌寵預設不開,要在「桌寵管理 → 插件」打開。
Text chat with your pets (group and one-on-one). Pets answer with their own reply lines; you can teach them phrases and correct them, and ask them to dance, sleep, sing or play with other pets. Works fully offline. Off for every pet by default; turn it on in Pet Manager → Plugins.

**MIDI 播放 / MIDI Player**:讓桌寵唱歌、一起合奏,讓家具播放音樂。附一套精簡音色庫,也可以匯入自己的 SoundFont。
Pets sing and play together, and furniture can play music. Includes a small built-in SoundFont; you can import your own.
⚠️ **不附任何 MIDI 檔**:請自己準備 `.mid` 檔,在「全局設定 → 插件 → MIDI 曲庫」匯入。
⚠️ **No MIDI files are included**: bring your own `.mid` files and import them under Global Settings → Plugins → MIDI library.

**小遊戲擴充包 / Mini-Game Pack**:新增小遊戲。目前有卡牌遊戲 Mau-Mau,可以跟桌寵、或讓桌寵之間對戰。
Adds mini-games. Currently the card game Mau-Mau, played against your pets or between pets.

## 怎麼安裝 How to install

1. 點上表的版本號,到該版本的發佈頁下載 `.sdpeplugin` 檔。
   Click a version above and download the `.sdpeplugin` file from its release page.
2. 在程式裡打開「全局設定」→「插件」,按「安裝插件…」選擇下載的檔案。只接受官方簽章的插件。
   In the app, open Global Settings → Plugins, press "Install plugin…" and choose the file. Only officially signed plugins are accepted.

已安裝的插件可以在同一頁按「檢查更新」。測試版(版本號結尾是 `b`,例如 `1.2.0b`)只有勾了「檢查更新時也通知測試版」才會通知,可能還有問題。
Installed plugins can be checked for updates on the same page. Beta versions (ending in `b`, e.g. `1.2.0b`) are only announced if you check "Also notify me about beta versions", and may still have problems.

## 授權與署名 License & credits

插件的程式碼以 [MIT 授權](LICENSE)釋出,與主程式相同([中文譯本](LICENSE.zh-TW.md))。插件附帶的第三方資料維持各自原本的授權,全文在每個插件安裝檔內的 `THIRD_PARTY_LICENSES.txt`;改編自 CC BY-SA 資料的部分同樣以 CC BY-SA 釋出。
Plugin code is released under the [MIT License](LICENSE), same as the app. Third-party data bundled with a plugin keeps its own license; full texts are in `THIRD_PARTY_LICENSES.txt` inside each plugin package, and material adapted from CC BY-SA data is likewise released under CC BY-SA.

<!-- plugin-credits:start -->
**小遊戲擴充包 / Mini-Game Pack**

- 程式碼 Code: MaltoseSlime (MIT)
- 沒有使用第三方素材或資料。No third-party assets or data.

**聊天 / Chat**

- 程式碼 Code: MaltoseSlime (MIT)
- [OpenCC](https://github.com/BYVoid/OpenCC) — Carbo Kuo and contributors (Apache 2.0)
- [CC-CEDICT](https://cc-cedict.org/) — MDBG and CC-CEDICT contributors (CC BY-SA 4.0)
- [VADER Sentiment Lexicon](https://github.com/cjhutto/vaderSentiment) — C.J. Hutto (MIT)

**MIDI 播放 / MIDI Player**

- 程式碼 Code: MaltoseSlime (MIT)
- [Godot MIDI Player](https://bitbucket.org/arlez80/godot-midi-player) — arlez80 (Yui Kinomoto) (MIT)
- [FluidR3Mono GM SoundFont](https://github.com/musescore/MuseScore/blob/main/share/sound/FluidR3Mono_License.md) — Frank Wen, Michael Cowgill (MIT)
<!-- plugin-credits:end -->

程式碼由 AI(Claude, Anthropic)協助撰寫;未使用 AI 生成的圖像素材。
Code written with AI assistance (Claude, Anthropic); no AI-generated art assets.

`index.json` 是程式檢查更新用的插件目錄,請不要手動改動格式。
`index.json` is the plugin directory the app reads when checking for updates.
