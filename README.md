# Open API Spec

## Getting started
1. Clone this repo
2. Overwrite the example content in `spec.yaml` with your open api specification
3. Install the chart:

``` bash
helm install . --namespace <your-namespace>
```

4. Clean up
```bash
helm delete <release-name> --purge
```