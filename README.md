# base-helm-chart
A helm chart to get up and running quickly with a deployment on kubernetes


## Values
```
replicaCount: 1

image:
  repository: nginx
  tag: ""

port: 4000

service:
  type: NodePort

url: example.com

# command : ["/bin/sh"]

# env:
#   - name: EXAMPLE_ENV
#   value: EXAMPLE_VALUE
```
