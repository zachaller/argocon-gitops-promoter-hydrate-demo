# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 00d6cc69206c539a57096eb869550b1dc51ab4ed
kustomize build ./user-configuration/production/us-west-1
```
