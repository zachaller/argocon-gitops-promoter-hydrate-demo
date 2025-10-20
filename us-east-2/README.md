# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 33519c000ba2f2c5a4604a7d6ee22fda9b15e9c4
kustomize build ./user-configuration/production/us-east-2
```
