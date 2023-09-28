# Packages

This repository host some packages as Helm charts and others.

## Content

* Helm charts:
    * [Cryptellation](https://cryptellation.dev)
    * [OTel-LGTM-Dev](https://github.com/lerenn/otel-lgtm-dev-chart)

## How-To

### Add index.yaml for a helm repository

```shell
helm repo index --url https://github.com/lerenn/packages/helm/<repo> ./helm/<repo> 
```

### Update index.yaml for a helm repository

```shell
helm repo index --url https://github.com/lerenn/packages/helm/<repo> --merge index.yaml ./helm/<repo>
```
