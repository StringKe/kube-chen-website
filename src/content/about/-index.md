---
title: "About KubChen"
meta_title: "About KubChen - Native Kubernetes Management"
description: "Learn about KubChen, the native desktop application for Kubernetes visualization and management"
image: "/images/avatar.png"
draft: false
---

## Our Mission

KubChen aims to make Kubernetes management accessible and efficient for everyone. We believe that visualizing your cluster resources should be the priority before any editing capabilities - you can't manage what you can't see.

## Why KubChen?

### Visualization First

Our core philosophy: **"Visualization comes before editing."** KubChen must fully display resource status, topology, and changes - otherwise, editing becomes meaningless. Every critical operation has a visual feedback loop: Get → Display → Explain → Operate → Confirm.

### Native Performance

Unlike browser-based or Electron alternatives, KubChen is built with:

- **Rust Backend**: Maximum performance and memory efficiency
- **Tauri 2 Framework**: Native system integration without the Electron overhead
- **React 19 Frontend**: Modern, responsive UI with the Mantine component library

### Open Source

KubChen is released under the PolyForm Noncommercial License, meaning:

- Free for personal use
- Free for open-source projects
- Full source code available on GitHub

## Technology Stack

| Layer | Technology |
|-------|------------|
| Backend | Rust 1.92, Tauri 2, kube-rs |
| Frontend | React 19, TypeScript, Mantine 8 |
| State | Jotai (atomic state management) |
| IPC | TauRPC (type-safe) |
| Platforms | macOS 11+, Windows 10+, Linux |

## Get Involved

- **GitHub**: [github.com/StringKe/kub-chen](https://github.com/StringKe/kub-chen)
- **Issues**: Report bugs or request features
- **Discussions**: Join the community conversation

---

Built with care by the open-source community.
