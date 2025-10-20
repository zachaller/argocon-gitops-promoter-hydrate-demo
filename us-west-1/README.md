# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 9497750226535ece45e64239bc5fabbbf6138ae5
kustomize build ./user-configuration/production/us-west-1
```
