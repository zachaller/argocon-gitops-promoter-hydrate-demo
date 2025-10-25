# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout de955e8fa9369c7728cddbd8d9d4e90aad7ff046
kustomize build ./user-configuration/staging/e2e
```
