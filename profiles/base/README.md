When profile-controller image updated, you can run below command to update it in manifest.

```
kustomize edit set image uhub.service.ucloud.cn/a4x-kubeflow/kubeflow-images-public/profile-controller:$NEW_TAG
```
