---
title: "Documentation"
meta_title: "KubeChen Documentation"
description: "Learn how to use KubeChen for Kubernetes cluster management"
draft: false
---

## Getting Started

### Installation

Download KubeChen from our [download page](/download) and follow the platform-specific instructions:

- **macOS**: Open the `.dmg` file and drag KubeChen to Applications
- **Windows**: Run the `.msi` installer
- **Linux**: Use the `.AppImage` or install the `.deb` package

### First Launch

1. Launch KubeChen
2. Your local kubeconfig clusters will be automatically discovered
3. Select a cluster from the sidebar to connect

---

## User Guide

### Cluster Connection

KubeChen automatically discovers clusters from your local `~/.kube/config` file. To connect:

1. Click on a cluster in the left sidebar
2. Wait for the connection to establish
3. Browse resources in the resource tree

### Resource Navigation

Resources are organized by category:

- **Workloads**: Pods, Deployments, StatefulSets, DaemonSets, Jobs, CronJobs
- **Network**: Services, Ingresses, NetworkPolicies
- **Storage**: PersistentVolumes, PersistentVolumeClaims, StorageClasses
- **Config**: ConfigMaps, Secrets
- **Access Control**: ServiceAccounts, Roles, RoleBindings

### Viewing Resources

Click any resource to view:

- **Overview**: Key metadata and status
- **YAML**: Full resource definition with syntax highlighting
- **Events**: Related Kubernetes events
- **Related**: Connected resources (e.g., Pods for a Deployment)

---

## Configuration

### Settings

Access settings via the gear icon or `Cmd/Ctrl + ,`:

- **Theme**: Light, Dark, or System
- **Language**: English, Chinese
- **Cluster Settings**: Connection timeout, refresh intervals

---

## Troubleshooting

### Connection Issues

**Problem**: Cannot connect to cluster

**Solutions**:
1. Verify your kubeconfig is valid: `kubectl cluster-info`
2. Check network connectivity to the API server
3. Ensure your credentials haven't expired

### Performance

**Problem**: Slow resource loading

**Solutions**:
1. Check the number of resources in the namespace
2. Try filtering by namespace instead of viewing all namespaces
3. Ensure your API server is responsive

---

## Contributing

KubeChen is open source! Visit our [GitHub repository](https://github.com/StringKe/kube-chen) to:

- Report bugs
- Request features
- Contribute code

---

Need help? [Open an issue](https://github.com/StringKe/kube-chen/issues) on GitHub.
