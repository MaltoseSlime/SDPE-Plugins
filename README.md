# SDPE Plugins

Slime Desktop Pet Editor(史萊姆桌寵編輯器)的官方插件。
Official plugins for Slime Desktop Pet Editor.

## 插件清單 Plugin list

<!-- plugin-list:start -->
| 插件 Plugin | 正式版 Stable | 測試版 Beta | 需要主程式 Requires app |
|---|---|---|---|
<!-- plugin-list:end -->

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
(還沒有發佈的插件。No plugins released yet.)
<!-- plugin-credits:end -->

程式碼由 AI(Claude, Anthropic)協助撰寫;未使用 AI 生成的圖像素材。
Code written with AI assistance (Claude, Anthropic); no AI-generated art assets.

`index.json` 是程式檢查更新用的插件目錄,請不要手動改動格式。
`index.json` is the plugin directory the app reads when checking for updates.
