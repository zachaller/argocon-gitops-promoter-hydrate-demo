# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout ed8494606296a2d57429113fe9aab45360b12baa
kustomize build ./user-configuration/production/us-west-1
```
