# Devfile Registry (Branch-per-Sample)

Custom devfile samples for OpenShift Dev Spaces.

## Structure

Each sample lives on its own branch with a `devfile.yaml` at the root:

| Branch | Description |
|--------|-------------|
| `python-2cpu` | Python environment with 2 CPU limit |
| `python-4cpu` | Python environment with 4 CPU limit |

## Deployment

Apply the ConfigMap to register samples in the Dev Spaces dashboard:

```bash
oc apply -f getting-started-samples.yaml
```
