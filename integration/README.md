# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e3359a331cf0855177f4c8716135b786f4a3475a
kustomize build ./user-configuration/staging/integration
```
