# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e5692b130820b2fe553358c9f4df8dfbc65b04ee
kustomize build ./user-configuration/staging/e2e
```
