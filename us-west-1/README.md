# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b9f19f8b54f380967390708e8d31f0418ebf7600
kustomize build ./user-configuration/production/us-west-1
```
