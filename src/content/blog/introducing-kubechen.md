---
title: "Introducing KubeChen: Native Kubernetes Management"
meta_title: "Introducing KubeChen - Native Kubernetes Visualization Tool"
description: "Announcing KubeChen, a new native desktop application for Kubernetes cluster visualization and management"
date: 2024-01-05T00:00:00Z
image: "/images/banner.png"
categories: ["Announcement"]
author: "KubeChen Team"
tags: ["kubernetes", "release", "open-source"]
draft: false
---

We're excited to introduce **KubeChen**, a native desktop application for Kubernetes cluster visualization and management.

## Why Another Kubernetes Tool?

Managing Kubernetes clusters often means juggling multiple tools: kubectl for CLI operations, web dashboards for visualization, and various third-party applications for specific tasks. We built KubeChen to provide a unified, native experience that prioritizes visualization and performance.

### Our Philosophy

**"Visualization comes before editing."**

We believe you can't effectively manage what you can't see. KubeChen is designed to give you complete visibility into your cluster resources before providing editing capabilities. Every critical operation follows a visual feedback loop:

1. **Get** - Retrieve resource data
2. **Display** - Show it clearly
3. **Explain** - Provide context
4. **Operate** - Enable action
5. **Confirm** - Verify results

## Key Features

### Multi-Cluster Support

Connect to multiple clusters from various sources:
- Local kubeconfig files
- AWS EKS
- Azure AKS
- Google GKE

### Native Performance

Built with **Rust** and **Tauri 2**, KubeChen delivers native performance without the overhead of Electron-based alternatives. The result is a lightweight application (~10MB) that's responsive and efficient.

### Modern UI

A clean, intuitive interface built with **React 19** and **Mantine** components, featuring:
- Resource tree navigation
- Real-time status updates
- YAML viewing with syntax highlighting
- Event streams and log viewing

## Open Source

KubeChen is released under the PolyForm Noncommercial License. It's free for:
- Personal use
- Open source projects
- Educational purposes

Check out the source code on [GitHub](https://github.com/StringKe/kube-chen).

## What's Next

We're currently in MVP development, focusing on:
- Core resource visualization
- Multi-cluster management
- Real-time monitoring

Stay tuned for our first official release!

---

Questions or feedback? [Open an issue](https://github.com/StringKe/kube-chen/issues) on GitHub.
