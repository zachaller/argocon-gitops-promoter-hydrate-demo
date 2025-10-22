# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout e693d919ed88024f6da2ac6e3937fb70dcb4f736
kustomize build ./user-configuration/staging/integration
```
