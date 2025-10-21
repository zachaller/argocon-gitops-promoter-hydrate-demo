# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/zachaller/argocon-gitops-promoter-hydrate-demo
# cd into the cloned directory
git checkout 214a0aebc63bf3f31be5dfc9725cc7ec77f03a57
kustomize build ./user-configuration/production/us-east-2
```
