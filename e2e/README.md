# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 3bdfcc9d5ce28c5bff5d50b3efb6cc7f129ee615
kustomize build ./user-configuration/staging/e2e
```
