## FrontierCut v1.12.6 — Windows & Playback Performance Overhaul

### 🚀 Highlights & Performance Improvements
- **GPU Hardware Rasterization on Windows**: Enabled DirectX/DirectComposition hardware acceleration, OOP canvas rasterization, and zero-copy video decoding to eliminate software rasterization and rendering lag.
- **Eliminated Window Drag Lag**: Scoped `-webkit-app-region: drag` to macOS only, eliminating continuous mousemove hit-testing overhead on Windows native frames.
- **Decoupled 60 FPS Playback Re-renders**: Isolated timecode and frame readouts into memoized subcomponents, removing root-level state subscriptions across headers, sidebars, toolbars, and inspector panels.
- **Fast Agent Backend Discovery**: Optimized backend binary survey with fast asynchronous filesystem scanning along PATH.

---

### 📦 Downloads & Verification

| Operating System | Architecture | Installer | Checksum |
| :--- | :--- | :--- | :--- |
| **macOS** | Apple Silicon (M1/M2/M3/M4) | [FrontierCut-1.12.6-macOS-arm64.dmg](https://github.com/teminali/frontiercut-releases/releases/download/v1.12.6/FrontierCut-1.12.6-macOS-arm64.dmg) | SHA-512 |
| **macOS** | Intel x86_64 | [FrontierCut-1.12.6-macOS-x64.dmg](https://github.com/teminali/frontiercut-releases/releases/download/v1.12.6/FrontierCut-1.12.6-macOS-x64.dmg) | SHA-512 |
| **Windows** | Windows 10/11 64-bit | [FrontierCut-Setup-1.12.6-Windows-x64.exe](https://github.com/teminali/frontiercut-releases/releases/download/v1.12.6/FrontierCut-Setup-1.12.6-Windows-x64.exe) | SHA-512 |
| **Linux** | Linux x86_64 | [FrontierCut-1.12.6-Linux-x86_64.AppImage](https://github.com/teminali/frontiercut-releases/releases/download/v1.12.6/FrontierCut-1.12.6-Linux-x86_64.AppImage) | SHA-512 |

---

### ✦ Model Context Protocol (MCP) Support
Connect Claude Code, Antigravity, or Gemini CLI to edit your video timeline live over local JSON-RPC.
