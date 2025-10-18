# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e3f4f538957395d92903a5c87423ef1eae59e889
kustomize build ./user-configuration/staging/integration
```
