[![Build Status](https://dev.azure.com/sfa-gov-uk/Apprenticeships%20Service%20Cloud%20Platform/_apis/build/status/das-api-stub-prototype?branchName=master)](https://dev.azure.com/sfa-gov-uk/Apprenticeships%20Service%20Cloud%20Platform/_build/latest?definitionId=2098&branchName=master)

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