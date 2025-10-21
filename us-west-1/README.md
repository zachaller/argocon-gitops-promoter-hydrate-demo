# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 85188db64dde1dd3762a961b39b81bc9e7315e90
kustomize build ./user-configuration/production/us-west-1
```
