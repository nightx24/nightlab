# 🌐 Google Chrome

## 🚩 Useful Chrome Flags

Chrome flags are experimental browser features that can change how Chrome behaves. Open `chrome://flags` in the address bar, search for a feature, then choose **Enabled** or **Disabled** and restart Chrome.

### 🔇 Tab Audio Muting UI

Adds a direct mute/unmute control to the audio indicator on a tab, making it quicker to silence a noisy website without opening the tab menu.

### ⚡ Parallel Downloading

Allows Chrome to split a download into multiple parts and fetch those parts simultaneously. It can improve download times for large files when the server and connection support multiple streams.

### 🌙 Auto Dark Mode for Web Contents

Automatically applies a dark appearance to websites that do not provide their own dark mode. Chrome adjusts page elements while generally preserving images, although some pages may display imperfect colors.

### 🖱️ Smooth Scrolling

Adds smoother scrolling animation to webpages. It can make scrolling feel less abrupt, especially on pages with long content.

### 🚀 Experimental QUIC Protocol

Enables Chrome's experimental QUIC networking protocol. QUIC uses UDP-based transport to reduce some connection overhead and can improve responsiveness on supported websites.

### 🎮 GPU Rasterization

Moves webpage rasterization work from the CPU to the GPU on supported systems. This can help with graphics-heavy webpages and leave more CPU resources available for other tasks.

### 🔄 Partial Swap

Controls Chrome's partial-update rendering behavior. If a webpage repeatedly reloads or displays a broken state after refresh, disabling this experimental feature may help in some cases, although it can affect loading performance.

### 📸 Incognito Screenshots — Android

Allows screenshots while using Chrome's Incognito mode on Android. Normally, Incognito pages may block screenshots; enabling this flag removes that restriction.

## 🛠️ How to Use Chrome Flags

1. Open Google Chrome.
2. Enter `chrome://flags` in the address bar.
3. Search for the feature you want to change.
4. Select **Enabled**, **Disabled**, or another available option.
5. Restart Chrome when prompted.
6. If something goes wrong, return to `chrome://flags` and use **Reset all** to restore the default flag settings.

> ⚠️ **Important:** Chrome flags are experimental. Their availability and behavior can change between Chrome versions, some flags may be removed, and enabling them can cause instability or unexpected behavior. Change one flag at a time when troubleshooting.
