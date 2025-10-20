# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 215aab6a54ed863fb4aedd5c92f120b05fdbd7b2
kustomize build ./user-configuration/production/us-west-1
```
