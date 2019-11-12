[![Latest Version](https://img.shields.io/github/release/softonic/kubewatch-chart.svg)](https://github.com/softonic/kubewatch-chart/releases)
[![Software License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](LICENSE)
[![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/softonic/kubewatch-chart.svg)](http://isitmaintained.com/project/softonic/kubewatch-chart "Average time to resolve an issue")
![GitHub issues](https://img.shields.io/github/issues-raw/softonic/kubewatch-chart)


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


If you want to know how the application works , follow this link's readme

https://github.com/softonic/kubewatch
