# base-helm-chart
A helm chart to get up and running quickly with a deployment on kubernetes


## Values

replicaCount: 1

image:
  repository: nginx
  tag: ""

service:
  type: NodePort
  port: 4000

url: example.com

env:
  # - name: EXAMPLE_ENV
  #   value: EXAMPLE_VALUE
