# helm-k8s-ecr-login-renew
A simple, lightweight chart for: https://github.com/nabsul/k8s-ecr-login-renew

Credit to:
1. https://github.com/nabsul/k8s-ecr-login-renew
2. @https://github.com/devec0 for this pull request: https://github.com/nabsul/k8s-ecr-login-renew/pull/28

This chart only takes a handful of values. 

* Be sure to specify a namespace when templating/installing a relaease!!! *

```
secretName: docker-ecr

ecr:
  region: ""
  accessKeyId: ""
  secretAccessKey: ""

image:
  repository: nabsul/k8s-ecr-login-renew
  tag: latest
  pullPolicy: IfNotPresent
 ```
