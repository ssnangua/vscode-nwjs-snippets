# VS Code NW.js snippets

This extension contains code snippets for NW.js for Vs Code editor.

![](images/test.gif)

## Installation

In order to install an extension you need to launch the Command Palette (Ctrl + Shift + P or Cmd + Shift + P) and type Extensions. There you have either the option to show the already installed snippets or install new ones. Search for _NW.js snippets_ and install it.

## _.js_ Snippets

All js snippets are start with `nw`:

- `nw.`: Official API
- `nw-`: Some useful code snippets

### `nw.`

| Trigger | API              |
| ------- | ---------------- |
| `nwa`   | `nw.App.*`       |
| `nwc`   | `nw.Clipboard.*` |
| `nwm`   | `nw.Menu.*`      |
| `nwp`   | `process.*`      |
| `nws`   | `nw.Screen.*`    |
| `nwshe` | `nw.Shell.*`     |
| `nwsho` | `nw.Shortcut.*`  |
| `nwt`   | `nw.Tray.*`      |
| `nww`   | `nw.webview.*`   |
| `nwwi`  | `nw.Window.*`    |

### `nw-`

| Prefix                        | Snippet Description                                            |
| ----------------------------- | -------------------------------------------------------------- |
| `nw-menubar`                  | Create a menubar                                               |
| `nw-contextmenu`              | Create a contextmenu                                           |
| `nw-tray`                     | Create a tray                                                  |
| `nw-globalHotKey`             | Register global hot key                                        |
| `nw-liveReload`               | Live reload current window                                     |
| `nw-liveReloadApp`            | Live reload app                                                |
| `nw-F5Reload`                 | Press F5 to reload current window                              |
| `nw-openBrowser`              | Open default browser                                           |
| `nw-openFile`                 | Open file                                                      |
| `nw-openFileManager`          | Open file manager                                              |
| `nw-openWindow`               | Open new window                                                |
| `nw-relaunchApp`              | Relaunch app                                                   |
| `nw-getCurrentScreen`         | Get current screen                                             |
| `nw-hideWindowInsteadOfClose` | Hide window instead of close                                   |
| `nw-draggable`                | Drag window by element                                         |
| `nw-getScript`                | Get script                                                     |
| `nw-ini`                      | Read and write .ini files.                                     |
| `nw-json`                     | Read and write .json files.                                    |
| `nw-drop-files`               | Get the dropped files.                                         |
| `nw-fs-read-dir`              | Reads the contents of a directory.                             |
| `nw-fs-read-dir-sync`         | (sync) Reads the contents of a directory.                      |
| `nw-fs-read-file`             | Reads a file.                                                  |
| `nw-fs-read-file-sync`        | (sync) Reads a file.                                           |
| `nw-fs-write-file`            | Writes data to a file.                                         |
| `nw-fs-write-file-sync`       | (sync) Writes data to a file.                                  |
| `nw-fs-copy`                  | Copies the entire directory structure from src to dest.        |
| `nw-fs-copy-sync`             | (sync) Copies the entire directory structure from src to dest. |
| `nw-fs-rename`                | Renames the file from oldPath to newPath.                      |
| `nw-fs-rename-sync`           | (sync) Renames the file from oldPath to newPath.               |
| `nw-fs-remove`                | Removes files and directories.                                 |
| `nw-fs-remove-sync`           | (sync) Removes files and directories.                          |
| `nw-cp-exec`                  | Executes a command.                                            |
| `nw-cp-exec-sync`             | (sync) Executes a command.                                     |
| `nw-cp-exec-file`             | Executes an executable file.                                   |
| `nw-cp-exec-file-sync`        | (sync) Executes an executable file.                            |

## _.css_ Snippets

| Prefix         | Snippet Description                    |
| -------------- | -------------------------------------- |
| `nw-draggable` | Draggable regions for frameless window |

## _.html_ Snippets

### \<input\>

| Prefix                                | Content                                              |
| ------------------------------------- | ---------------------------------------------------- |
| `input[nwdirectory][nwdirectorydesc]` | `<input type="file" nwdirectory nwdirectorydesc="">` |
| `input[nwsaveas]`                     | `<input type="file" nwsaveas="">`                    |
| `nwworkingdir`                        | `nwworkingdir`                                       |

### \<iframe\>

| Prefix        | Content          |
| ------------- | ---------------- |
| `nwdisable`   | `nwdisable`      |
| `nwfaketop`   | `nwfaketop`      |
| `nwUserAgent` | `nwUserAgent=""` |

### \<webview\>

| Prefix    | Content                                     |
| --------- | ------------------------------------------- |
| `webview` | `<webview id="" src="" style=""></webview>` |
| `allownw` | `allownw`                                   |

### \<script\>

| Prefix                    | Content                                  |
| ------------------------- | ---------------------------------------- |
| `script:src[type=module]` | `<script src="" type="module"></script>` |

## _.json_ Snippets

| Prefix | Snippet Description |
| ------- | ------- |
| `nw-package-json` | Insert full manifest fields to package.json |
| `nw-cmd--*` | For `chromium-args`, includes: `--url`, `--mixed-context`, `--nwapp`, `--user-data-dir`, `--disable-devtools`, `--enable-node-worker`, `--disable-raf-throttling`, `--disable-cookie-encryption`, `--disable-crash-handler=true`, `--enable-gcm`, `--enable-transparent-visuals`, `--disable-transparency`, `--force-cpu-draw` |

## Note

- About `nw.win.cookies`, see [chrome.cookies](https://developer.chrome.com/docs/extensions/reference/cookies/).
