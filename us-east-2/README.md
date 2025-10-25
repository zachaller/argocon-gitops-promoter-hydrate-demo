# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout b35dc07b65fdeb9f34dc806832f925a92d9cf1da
kustomize build ./user-configuration/production/us-east-2
```
