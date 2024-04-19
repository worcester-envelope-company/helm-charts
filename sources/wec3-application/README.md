# wec3-application

- creates a deployment, service and ingress

- deployment pulls configuration data from a secret with "-config" appended to the deployment name

- ingress is created with ssl by deafult

### test chart

```
helm lint ./ -f test-values.yaml
```
