# simplism-on-k8s

This is the companion project of this blog posts:
- https://k33g.hashnode.dev/deploy-wasm-functions-on-kubernetes-with-simplism
- https://k33g.hashnode.dev/deploy-wasm-functions-on-kubernetes-with-simplism-1


## Download the wasm file samples

```bash
wget https://raw.githubusercontent.com/bots-garden/simplism/main/k8s/wasm-files/hello-world.wasm -O ./wasm-files/hello-world.wasm
wget https://raw.githubusercontent.com/bots-garden/simplism/main/k8s/wasm-files/small-cow.wasm -O ./wasm-files/small-cow.wasm
wget https://raw.githubusercontent.com/bots-garden/simplism/main/k8s/wasm-files/small_ant.wasm -O ./wasm-files/small_ant.wasm
```

## Download the manifest files

```bash
wget https://github.com/bots-garden/simplism/releases/download/v0.1.3/deploy-wasm-from-remote.yaml -O ./manifets/deploy-wasm-from-remote.yaml
wget https://github.com/bots-garden/simplism/releases/download/v0.1.3/wasm-files-volume.yaml -O ./manifets/wasm-files-volume.yaml
wget https://github.com/bots-garden/simplism/releases/download/v0.1.3/deploy-wasm-from-volume.yaml -O ./manifets/deploy-wasm-from-volume.yaml

wget https://github.com/bots-garden/simplism/releases/download/v0.1.3/wasm-registry-volume.yaml -O ./manifets/wasm-registry-volume.yaml
wget https://github.com/bots-garden/simplism/releases/download/v0.1.3/deploy-wasm-registry.yaml -O ./manifets/deploy-wasm-registry.yaml

wget https://github.com/bots-garden/simplism/releases/download/v0.1.3/deploy-wasm-from-registry.yaml -O ./manifets/deploy-wasm-from-registry.yaml
```
