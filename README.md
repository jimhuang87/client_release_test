# QNote Client release feed

Velopack 自動更新用的 release feed。
由 qnote_tools.git/qnote_client/release.ps1 透過 `vpk upload github` 發佈，請不要手動編輯 release 內的檔案。

- `qnote_client-win-Setup.exe`  新機器的安裝程式
- `qnote_client-<ver>-full.nupkg` / `-delta.nupkg`  更新套件
- `releases.win.json`  update feed 索引