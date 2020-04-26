# shlink-helm-chart
A helm chart to deploy [Shlink](https://shlink.io) to Kubernetes

# Usage
Clone this repository and run the following command
```
helm install shlink path/to/repo/shlink \
    --set "ingress.enabled=true" \
    --set "env.SHORT_DOMAIN_HOST=<short_domain>" \
```
Please refer to the values.yaml file to see the complete list of variables that can be set.