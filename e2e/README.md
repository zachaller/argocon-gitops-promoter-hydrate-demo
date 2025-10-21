# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 59030f436b2834850bb9e5e6ef8b4172880a69cd
kustomize build ./user-configuration/staging/e2e
```
