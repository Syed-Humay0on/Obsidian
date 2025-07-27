---
id: Devpods-setup
aliases: []
tags: []
---
# Setup Devpod using Docker provider

## Install Devpod cli from official [Devpods.sh](https://devpod.sh/docs/getting-started/install)

> [!Note]
> since I'm using arch on AMDx64 system so I'm gonna be using that link
    
```
curl -L -o devpod "https://github.com/loft-sh/devpod/releases/latest/download/devpod-linux-amd64" && sudo install -c -m 0755 devpod /usr/local/bin && rm -f devpod 
```

## After installing devpod-cli, check the version
```
    devpod version
```

## Add a Provider
You can add a provider via (local-docker for example):
```
devpod provider add docker
```

