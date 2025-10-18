# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 24fee31e03d10e3b88fe7afd2216f0dc4055dcf0
kustomize build ./user-configuration/staging/integration
```
