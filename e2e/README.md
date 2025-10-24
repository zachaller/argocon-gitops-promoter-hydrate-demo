# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 712fd367762509110bfd7ea678a8156205c0339b
kustomize build ./user-configuration/staging/e2e
```
