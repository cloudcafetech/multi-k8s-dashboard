# Kore Board :whale:
> Kubernetes multi-clusters dashboard

![Version](https://img.shields.io/github/release/kore3lab/dashboard) ![License](https://img.shields.io/github/license/kore3lab/dashboard) ![code size](https://img.shields.io/github/languages/code-size/kore3lab/dashboard)  ![issues](https://img.shields.io/github/issues/kore3lab/dashboard) ![issues](https://img.shields.io/github/issues-closed/kore3lab/dashboard) ![pull requests](https://img.shields.io/github/issues-pr-closed/kore3lab/dashboard) 

Kore-board is a web-based UI for Kubernetes multi-clusters management.  It allows users to manage applications running in the multi-clusters as well as the cluster itself.

## Features

### Easy Kubernetes multi-clusters management.

![intuitive-user-experience-add-a-cluster](./docs/images/feat-intuitive-user-experience-add-a-cluster.gif)

### Provides an intuitive user experience interface.

![intuitive-user-experience-pods](./docs/images/feat-intuitive-user-experience-pods.gif)

### Provides enhanced visibility of the Kubernetes clusters.

![cluster-visualization](./docs/images/feat-cluster-visualization.gif)

### Supports cluster and pod terminal mode.

![cluster-and-pod-terminal](./docs/images/feat-cluster-and-pod-terminal.gif)

## Getting Started

### Installation

```
kubectl apply -f https://raw.githubusercontent.com/cloudcafetech/multi-k8s-dashboard/refs/heads/master/scripts/install/kubernetes/recommended.yaml
```

See [Installation Guide](./docs/user/installation.md) page for more information

### Access

1. Open in your browser `http://<cluster-ip>:30070/`
2. On the sign-in page, enter "admin2675" as a token string and sign in

## [Documentation](./docs/README.md)

* See [User Guide](./docs/user/README.md) page.
* See [Sign in Guide](./docs/user/config-sign-in.md) page.

## Demo

[![Screenshot](./docs/images/sc-youtube.jpg)](https://www.youtube.com/watch?v=Z75pBBqL0u8)

## Contribution

See [Contributing](./CONTRIBUTING.md) page.
