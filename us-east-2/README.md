# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 423955c1ddbd1aeaf4f694b1688bb7af82bb0bbb
kustomize build ./user-configuration/production/us-east-2
```
