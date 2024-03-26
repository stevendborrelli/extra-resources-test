# Overview

An example of using <https://github.com/crossplane-contrib/function-extra-resources> to render ProviderConfigs.

## Rendering

```shell
crossplane beta render example/xawsproviderconfig.yaml apis/composition.yaml example/functions.yaml -r --extra-resources=example/envconfig.yaml
```
