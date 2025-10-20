# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 92c462d1ead947a3093afd2fe270abf0a2dcb4a4
kustomize build ./user-configuration/staging/e2e
```
