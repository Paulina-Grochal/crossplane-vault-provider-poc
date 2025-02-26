# Crossplane with Vault Provider PoC

Simple crossplane example how to use a vault provider.

## Prerequisites

Before applying resources make sure you have vault and crossplane running on your cluster.

### Steps

Install vault provider.
```
kubectl apply -f vault-provider.yaml
```

Update your token (or other auth method) and apply the provider config.
```
kubectl apply -f vault-provider-config.yaml
```

Now you are redy to use it!