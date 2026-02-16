# Binary Packers

Tools that bundle your app into a binary for distribution.

## TL;DR

Best overall balance (2026): **Tauri**
Fastest to ship: Electron
Smallest & cleanest: Neutralino
Most experimental charm: GemShell

| Dimension                 | **Electron**     | **Tauri**                          | **Neutralino**    | **GemShell**            |
| ------------------------- | ---------------- | ---------------------------------- | ----------------- | ----------------------- |
| **Rendering engine**      | Bundled Chromium | System WebView (WebKit / WebView2) | System WebView    | GTK WebKit              |
| **Backend language**      | Node.js (JS/TS)  | Rust core (optional for you)       | C++ core (hidden) | Python                  |
| **JS-only app possible?** | ✅ Yes            | ✅ Yes                              | ✅ Yes             | ⚠️ Mostly yes        |
| **Typical app size**      | 80–150 MB        | 5–15 MB                            | 2–5 MB            | 10–30 MB                |
| **Memory footprint**      | Heavy            | Light                              | Very light        | Light                   |
| **Startup speed**         | Slow–medium      | Fast                               | Very fast         | Fast                    |
| **Security model**        | Weak by default  | Strong by design                   | Minimal           | Depends on Python setup |
| **Mobile friendliness**   | ❌ No             | ⚠️ Experimental                    | ❌ No              | ❌ No                 |
| **Ecosystem size**        | Massive          | Growing fast                       | Small             | Tiny                    |
| **Maturity**              | Very mature      | Mature                             | Mature but niche  | Experimental / niche    |


- [Electron](https://www.electronjs.org/)
  Classic.

- [Tauri](https://tauri.app/)
  A Rust tool that "builds your app for Linux, macOS, Windows, Android and iOS
  all from a single codebase. Write your frontend in JavaScript, application
  logic in Rust, and integrate deep into the system with Swift and Kotlin.

  Tauri is the only one that considers security.

- [GemShell](https://gemshell.dev/)
  Specific for games.

  > A GUI tool that wraps your HTML5 game into a desktop app with Steamworks.
  > No Electron boilerplate, no build scripts - just your game folder and a few
  > clicks.

- [Neutralino](https://neutralino.js.org/)
  > Build lightweight cross-platform desktop apps with JavaScript, HTML, and
  > CSS

