# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout f61be78b9b76d4dfacef85a0bcef34c432cbd2ab
kustomize build ./user-configuration/staging/e2e
```
