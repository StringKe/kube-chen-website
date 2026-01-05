---
title: "Download"
meta_title: "Download KubChen - Native Kubernetes Management"
description: "Download KubChen for macOS, Windows, or Linux"
draft: false
---

## Download KubChen

KubChen is currently in **MVP development** (v0.1.0). Releases will be available soon.

### Coming Soon

| Platform | Architecture | Status |
|----------|--------------|--------|
| macOS | Apple Silicon (arm64) | In Development |
| macOS | Intel (x64) | In Development |
| Windows | x64 | In Development |
| Linux | x64 (.AppImage) | In Development |
| Linux | x64 (.deb) | In Development |

### Build from Source

While we prepare official releases, you can build KubChen from source:

```bash
# Clone the repository
git clone https://github.com/StringKe/kub-chen.git
cd kub-chen

# Install dependencies (requires Rust 1.92+ and Node.js 22+)
npm install

# Run in development mode
npm run tauri:dev

# Build for production
npm run tauri:build
```

### Requirements

- **Rust**: 1.92 or later
- **Node.js**: 22 or later
- **Platform Tools**: Xcode (macOS), Visual Studio Build Tools (Windows), or build-essential (Linux)

---

## Stay Updated

- **GitHub**: [Watch releases](https://github.com/StringKe/kub-chen/releases)
- **Star the repo**: Help us grow the community

---

Questions? Check our [documentation](/docs) or [open an issue](https://github.com/StringKe/kub-chen/issues).
