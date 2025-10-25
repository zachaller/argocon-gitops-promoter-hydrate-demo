# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 24cec7c4f1b5c0db8d185f7ab217777aee093ec6
kustomize build ./user-configuration/production/us-west-1
```
