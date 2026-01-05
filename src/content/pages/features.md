---
title: "Features"
meta_title: "KubChen Features - Complete Kubernetes Management"
description: "Explore the powerful features of KubChen for Kubernetes cluster management"
draft: false
---

## Core Features

### Multi-Cluster Management

Connect and manage multiple Kubernetes clusters from a single interface:

- **Local Kubeconfig**: Auto-import clusters from your local kubeconfig file
- **Cloud Provider Discovery**: Automatic discovery for AWS EKS, Azure AKS, and GCP GKE
- **Context Management**: Quick switching between clusters with connection status monitoring
- **Credential Caching**: Secure credential storage for seamless reconnection

### Resource Visualization

See your entire cluster at a glance:

- **Resource Tree**: Navigate resources organized by type (Workloads, Network, Storage, Config, Access Control)
- **Resource List**: Filterable, searchable, sortable lists with customizable columns
- **Status Indicators**: Visual badges showing resource health and status
- **Detail Panel**: YAML view, events, and related resources in one place

### Real-time Monitoring

Stay informed about your cluster's state:

- **Overview Dashboard**: Cluster-wide CPU, memory, Pod counts, and Node health
- **Event Stream**: Real-time events with level filtering (Warning, Error, Normal)
- **Log Viewer**: Multi-container Pod logs with follow mode and time filtering
- **Namespace Statistics**: Resource breakdown by namespace

### Use Cases

| Scenario | Operations | Development |
|----------|------------|-------------|
| **Troubleshooting** | Quick Pod identification, events, logs | Workload status viewing |
| **Health Checks** | Multi-cluster health overview | Dependency discovery |
| **Change Management** | YAML editing (coming soon) | Deployment editing (coming soon) |
| **Access Control** | RBAC management | Namespace permissions |

---

## Technical Architecture

```
┌─────────────────────────────────────────┐
│           React 19 Frontend             │
│    Mantine UI + Jotai State + i18n     │
└──────────────────┬──────────────────────┘
                   │ TauRPC (Type-safe IPC)
┌──────────────────┴──────────────────────┐
│           Rust Backend (Tauri 2)        │
│    kube-rs + Tokio + SQLite            │
└──────────────────┬──────────────────────┘
                   │
┌──────────────────┴──────────────────────┐
│         Kubernetes API Server           │
└─────────────────────────────────────────┘
```

## Platform Support

| Platform | Minimum Version | Architecture |
|----------|----------------|--------------|
| macOS | 11.0 (Big Sur) | Intel & Apple Silicon |
| Windows | 10 | x64 |
| Linux | Ubuntu 18.04+ | x64 |

---

Ready to get started? [Download KubChen](/download) today.
