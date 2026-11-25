# Kivra Launcher

**Kivra Launcher** is a fast, lightweight, ad-free Minecraft launcher with zero telemetry — built for **Minecraft: Java Edition** and **Bedrock Edition** (Windows).

## Features

- **Mod & Modpack Ecosystem:** Live search and 1-click install from **Modrinth** and **CurseForge** (plus **MCPEDL** for Bedrock). Supports **Vanilla, Fabric, Quilt, Forge, and NeoForge**, `.mrpack` / `.zip` import & export, automatic dependency resolution, `Installed` status badges, duplicate cleanup, and 1-click FPS optimization.
- **Friends, Chat & P2P Multiplayer:** Add friends by nickname (no friend codes needed). Includes `# General chat`, direct messages, 1-click modpack sharing, and P2P singleplayer world hosting without port forwarding.
- **Voice, Video & 4K Screen Sharing:** Discord-style WebRTC calls with **4K / 2K / 1080p (60 FPS)** screen sharing and a fullscreen stream viewer with mouse-wheel zoom (`100%–400%`) and drag-to-pan.
- **Flexible Accounts & Skins:** Supports **Microsoft**, **Ely.by** (with 2FA), and **Offline** accounts. Includes a built-in **3D Skin Viewer & Pixel Editor**, cape manager, and wardrobe import from other launchers.
- **Built-in AI Assistant:** Connect **Gemini, OpenAI, Claude, DeepSeek, Groq, OpenRouter, Mistral, Ollama**, or a custom OpenAI-compatible endpoint to analyze crash logs, manage instances, and build modpacks.
- **Pulse Visuals HUD (Optional):** Toggleable dark frosted-glass Fabric/Quilt client overlay (heart-based Target HUD, floating damage numbers, Keystrokes + CPS, live FPS & Ping graph) controllable in Settings.
- **21 Languages & Custom Themes:** Dark, green, light, or custom color palettes, Windows desktop notifications, screenshot gallery, and server browser.

## Download

Download the latest Windows installer or portable build from the **Releases** page:
- `KivraLauncher-Setup-0.1.0.exe` — Windows Installer
- `KivraLauncher-Portable-0.1.0.exe` — Windows Portable

## Development

```bash
npm install
npm start        # Run launcher in development mode
npm test         # Run unit & UI smoke tests
npm run dist:win # Build Windows installer & portable .exe
```
