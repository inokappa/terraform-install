## terraform-install for wercker step

terraform install and ruby install for wercker step.

### how to use

Add ${terraform-version}.(ex: 0.6.2)

```yaml
build:
  steps:
    - inokappa/terraform-install:
        version: ${terraform-vresion}
```
