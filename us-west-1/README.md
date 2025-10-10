# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout a70abc1d681d73d9afee7ac4beee3ea987e8dfad
kustomize build ./user-configuration/production/us-west-1
```
