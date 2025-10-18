# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ab1b1163d98b75bebc563398e19bac6774adb215
kustomize build ./user-configuration/staging/e2e
```
