---
title: "Helm 获取钩子"
---

## helm get hooks

下载命名版本的所有钩子

### 简介

该命令下载指定版本的钩子

钩子被格式化为YAML格式并以YAML的'---\n'分隔符分隔

```shell
helm get hooks RELEASE_NAME [flags]
```

### 可选项

```shell
  -h, --help           help for hooks
      --revision int   get the named release with revision
```

### 从父命令继承的命令

```shell
      --debug                       enable verbose output
      --kube-apiserver string       the address and the port for the Kubernetes API server
      --kube-as-group stringArray   Group to impersonate for the operation, this flag can be repeated to specify multiple groups.
      --kube-as-user string         Username to impersonate for the operation
      --kube-context string         name of the kubeconfig context to use
      --kube-token string           bearer token used for authentication
      --kubeconfig string           path to the kubeconfig file
  -n, --namespace string            namespace scope for this request
      --registry-config string      path to the registry config file (default "~/.config/helm/registry.json")
      --repository-cache string     path to the file containing cached repository indexes (default "~/.cache/helm/repository")
      --repository-config string    path to the file containing repository names and URLs (default "~/.config/helm/repositories.yaml")
```

### 请参阅

* [helm get](helm_get.md) - 下载命名版本的扩展信息
