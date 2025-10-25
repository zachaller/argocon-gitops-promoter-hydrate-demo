# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 80252db619a5cf8cd8b16e215ae8707e89d68046
kustomize build ./user-configuration/staging/integration
```
