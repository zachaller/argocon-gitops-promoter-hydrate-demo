# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b721db8f253b9d5064bf698257ac970e84b06bf1
kustomize build ./user-configuration/staging/integration
```
