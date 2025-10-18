# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 70c6a388865a26f6348626e3b78b3b007f226439
kustomize build ./user-configuration/production/us-east-2
```
