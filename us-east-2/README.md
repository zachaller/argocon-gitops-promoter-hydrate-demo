# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 2b797ad6b519b57f3281aeba5ce5eb11110e0191
kustomize build ./user-configuration/production/us-east-2
```
