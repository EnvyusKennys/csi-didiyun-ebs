[![Actions Status](https://github.com/supremind/csi-didiyun-ebs/workflows/csi-didiyun-ebs/badge.svg)](https://github.com/supremind/csi-didiyun-ebs/actions?query=workflow%3A%22csi-didiyun-ebs%22)
[![Coverage Status](https://coveralls.io/repos/github/supremind/csi-didiyun-ebs/badge.svg?branch=master)](https://coveralls.io/github/supremind/csi-didiyun-ebs?branch=master)
[![Go Report Card](https://goreportcard.com/badge/github.com/supremind/csi-didiyun-ebs)](https://goreportcard.com/report/github.com/supremind/didiyun-client) 

# Didiyun EBS CSI Plugin

Unofficial plugin to use Didiyun EBS as a PVC in Kubernetes.

## Deploy

```
helm repo add csi-didiyun-ebs https://supremind.github.io/csi-didiyun-ebs/charts
helm repo update
helm upgrade --install csi-ebs csi-didiyun-ebs/csi-didiyun-ebs --namespace didiyun --create-namespace --version 0.1.0 -f ./examples/values.yaml
```

## Contributors
- [@kelviN](https://github.com/killwing)
- [@houz42](https://github.com/houz42)
