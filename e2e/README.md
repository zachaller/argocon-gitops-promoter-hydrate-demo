# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 7e6ba74fdb04930b588884f3598701e303135889
kustomize build ./user-configuration/staging/e2e
```
