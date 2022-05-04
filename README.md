# VS Code NW.js snippets

This extension contains code snippets for NW.js for Vs Code editor.

![](images/test.gif)

## Installation

In order to install an extension you need to launch the Command Palette (Ctrl + Shift + P or Cmd + Shift + P) and type Extensions. There you have either the option to show the already installed snippets or install new ones. Search for *NW.js snippets* and install it.

## *.js* Snippets

All js snippets are start with `nw`:
- `nw.`: Official API
- `nw-`: Some useful code snippets

### `nw.`
| Trigger | API |
| ------- | ------- |
| `nwa`   | `nw.App.*` |
| `nwc`   | `nw.Clipboard.*` |
| `nwm`   | `nw.Menu.*` |
| `nwp`   | `process.*` |
| `nws`   | `nw.Screen.*` |
| `nwshe` | `nw.Shell.*` |
| `nwsho` | `nw.Shortcut.*` |
| `nwt`   | `nw.Tray.*` |
| `nww`   | `nw.webview.*` |
| `nwwi`  | `nw.Window.*` |

### `nw-`

| Prefix | Snippet Description |
| ------- | ------- |
| `nw-menubar` | Create a menubar |
| `nw-contextmenu` | Create a contextmenu |
| `nw-tray` | Create a tray |
| `nw-globalHotKey` | Register global hot key |
| `nw-liveReload` | Live reload current window |
| `nw-liveReloadApp` | Live reload app |
| `nw-F5Reload` | Press F5 to reload current window |
| `nw-openBrowser` | Open default browser |
| `nw-openFile` | Open file |
| `nw-openFileManager` | Open file manager |
| `nw-openWindow` | Open new window |
| `nw-relaunchApp` | Relaunch app |
| `nw-getCurrentScreen` | Get current screen |
| `nw-hideWindowInsteadOfClose` | Hide window instead of close |

## *.css* Snippets

| Prefix | Snippet Description |
| ------- | ------- |
| `nw-draggable` | Draggable regions for frameless window |

## *.html* Snippets

### \<input\>

| Prefix | Content |
| ------- | ------- |
| `input[nwdirectory][nwdirectorydesc]` | `<input type="file" nwdirectory nwdirectorydesc="">` |
| `input[nwsaveas]` | `<input type="file" nwsaveas="">` |
| `nwworkingdir` | `nwworkingdir` |

### \<iframe\>

| Prefix | Content |
| ------- | ------- |
| `nwdisable` | `nwdisable` |
| `nwfaketop` | `nwfaketop` |
| `nwUserAgent` | `nwUserAgent=""` |

### \<webview\>

| Prefix | Content |
| ------- | ------- |
| `webview` | `<webview id="" src="" style=""></webview>` |
| `allownw` | `allownw` |

## *.json* Snippets

| Prefix | Snippet Description |
| ------- | ------- |
| `nw-package-json` | Insert full manifest fields to package.json |
| `nw-cmd--*` | For `chromium-args`, includes: `--url`, `--mixed-context`, `--nwapp`, `--user-data-dir`, `--disable-devtools`, `--enable-node-worker`, `--disable-raf-throttling`, `--disable-cookie-encryption`, `--disable-crash-handler=true`, `--enable-gcm`, `--enable-transparent-visuals`, `--disable-transparency`, `--force-cpu-draw` |

## Note

- About `nw.win.cookies`, see  [chrome.cookies](https://developer.chrome.com/docs/extensions/reference/cookies/).