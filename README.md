# Scratch Lite

Scratch Lite is a custom desktop distribution of Scratch that is approximately 4x smaller than the official version. 

By utilizing the **Tauri** framework and **Rust** instead of Electron, this version significantly reduces resource overhead and disk space, making it ideal for low-spec hardware or systems with limited storage.

## Why?

I had a 64GB eMMC drive before but even though I know have a PCIe Gen4 500GB SSD I wanted to see if i could do it.

## Key Differences
- **Framework:** Built with Tauri (using the system's native webview, WebView2 on windows) instead of bundling a full Chromium browser.
- **Size:** Approximately 108MB installer compared to the 400MB+ installed size of the official app.
- **Performance:** Lower RAM idle usage and faster cold-boot times on Windows.

## Technical Details
- **Core:** Based on the [scratch-gui](https://github.com/scratchfoundation/scratch-gui) repository.
- **Frontend:** React and Webpack.
- **Backend:** Rust (Tauri).

## Installation
Download the latest executable from the [Releases](https://github.com) page. Run the setup file to install Scratch Lite to your applications menu.

## Credits
This isn't affiliated with scratch, it's just something I made. Scratch was made by MIT.
