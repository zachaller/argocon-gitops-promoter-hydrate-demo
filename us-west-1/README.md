# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 217e2e020f1d0f901bbe8d5875ee742d4f8e6834
kustomize build ./user-configuration/production/us-west-1
```
