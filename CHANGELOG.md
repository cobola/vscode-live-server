# Changelog

| Version | Date | Changelog |
|---|---|---|
|1.6.5|26.07.17|Bug Fixed for Linux & macOS. Sometime extension was crashing if `liveServer.settings.CustomBrowser` settings is not provided by manually on macOS & Linux. |
|1.6.4|26.07.17|Critical Bug Fixed for Linux & macOS. Extension was crashing for `liveServer.settings.root` settings on macOS & Linux. |
|1.6.3| 24.07.17 | Validation added for Port range. |
|1.6.2| 22.07.17 | Fixed error handling for unavailable port. |
|1.6.1|20.07.17|Fixed Update - Extension was not opening system's default browser. _[Sorry for that, Extension was crashing internally]_|
|1.6.0|19.07.17| &mdash; [[#5](https://github.com/ritwickdey/vscode-live-server/issues/5)] New Settings - `liveServer.settings.AdvanceCustomBrowserCmdLine` - Now set your any favorite browser (Eg: Chrome Canary, Firefox Nightly) for Live Server using advance Command Line. (_[More Info.](https://github.com/ritwickdey/vscode-live-server#settings)_) [Thanks [Obinna A. Kalu](https://github.com/obkalu)]. <br><br> &mdash; Support for Microsoft-Edge through `liveServer.settings.CustomBrowser` settings.  |
|1.5.0 | 17.07.17 | [[Quick Gif Demo](./images/Screenshot/ChromeDebugging.gif)] New Feature Added - Support for Chrome Debugging Attachment. (You have to enable the feature through `liveServer.settings.ChromeDebuggingAttachment` settings. _[More Info.](https://github.com/ritwickdey/vscode-live-server#settings)_).  [Thanks [Obinna A. Kalu](https://github.com/obkalu) [[#5](https://github.com/ritwickdey/vscode-live-server/issues/5)] ].
|1.4.4 | 12.07.17 | Validation Pattern is added for root settings & Custom Browser settings is fixed. Package size reduced.
|1.4.3 | 10.07.17 | Status-bar Icon added. Minor Fix update on Status bar control. |
|1.4.2|08.07.17|Minor Fix Update on Custom Browser Setting.|
|1.4.1 | 07.07.17 | Minor Fix Update. (Thanks [Adam](https://github.com/AdamLombard)) [[#4](https://github.com/ritwickdey/vscode-live-server/pull/4)]. |
|1.4.0 | 04.07.17 | Two new settings are added. <br> &mdash; 1. `liveServer.settings.root` to change root of server in between workspace folder structure. (Thanks _[zorgoz](https://github.com/zorgoz)_ for the suggestion) [[#2](https://github.com/ritwickdey/vscode-live-server/issues/2)].<br> &mdash; 2. `liveServer.settings.CustomBrowser` to change default browser.<br> <br> &mdash; Bug Fixed - `Cannot GET/ Error` when server starts with a html file located sub folder of root. (Thanks _[John Michael Robin](https://github.com/jmmrdev)_ for reporting the bug) [[#3](https://github.com/ritwickdey/vscode-live-server/issues/3)].
| 1.3.1 | 03.07.17 | File Extension detection issue is fixed, `Live Server` will be activated if there have atleast one HTML except in your `node_modoules` directory and description of extension updated as git repo name of the extension is updated to conventional name | 
| 1.3.0 | 02.07.17 |`Go Live` option on Statusbar will be appeared if HTML file is opened or if there have at least one HTML file in workspace.(Thanks _[Yu Zhang](https://github.com/neilsustc)_) [[#1](https://github.com/ritwickdey/vscode-live-server/issues/1)].|
| 1.2.0 | 30.06.17 | Settings for Customizing Port No of Live Server. Small UX updated. |
| 1.1.1 | 30.06.17 | Keyboad Shortcuts has been changed to `ALT+L, O` and `ALT+L, C` due to `Shift+ANY_CHARACTER` has different meaning - sorry for that.
| 1.1.0 | 30.06.17 | Editor/Context Menu Shortcut & Keyboad Shortcut added, Changelog added and Readme updated. |
| 1.0.0 | 29.06.17 | Fixed - issue in Server closing. |
| 0.2.0 | 28.06.17 | Status Bar control & User Experience updated and bugs Fixed. |
| 0.1.0 | 28.06.17 | Live Server Port details added, Bugs fixed & improvement. |
| 0.0.2 | 28.06.17 | Extension Icon & description added. |
| 0.0.1 | 28.06.17 | Initial Release. |
