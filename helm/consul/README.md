### Add the HashiCorp Helm Repository:

```bash
helm repo add hashicorp https://helm.releases.hashicorp.com
```

### Installing Consul on Kubernetes using Helm

```bash
helm install consul hashicorp/consul --set global.name=consul --create-namespace --namespace consul --values values.yaml
```