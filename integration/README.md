# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e3b6db0e99b01f363aefffd53edbe80c76ab2101
kustomize build ./user-configuration/staging/integration
```
