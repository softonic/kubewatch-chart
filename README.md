# Kubewatch 

### Overview



| Parameter                                           | Description                                                   | Default                            |
| --------------------------------------------------- | ------------------------------------------------------------- | ---------------------------------- |
| `replicaCount`                                      | Number of deployment replicas                                 | `1`                                |
| `image.repository`                                  | Image repo                                                    | `softonic/kubewatch`               |
| `image.tag`                                         | Tag used for the image                                        | `v0.4.0`                           |
| `image.pullPolicy`                                  | Image pull secret                                             | `IfNotPresent`                     |
| `resources.limits.memory`                           | Resources limits for memory for kubewatch container           | `32Mi`                             |
| `resources.limits.cpu`                              | Resources limits for CPU for kubewatch container              | `100m`                             |
| `resources.requests.memory`                         | Resources requests for memory for kubewatch container         | `32Mi`                             |
| `resources.requests.cpu`                            | Resources requests for cpu for kubewatch container            | `100m`                             |



```
replicaCount: 1
image:
  repository: softonic/kubewatch
  tag: v0.4.0
  pullPolicy: IfNotPresent
resources:
  limits:
    cpu: 100m
    memory: 32Mi
  requests:
    cpu: 100m
    memory: 32Mi
```
