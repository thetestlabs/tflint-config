# tflint-config

A shared TFLint configuration file for Terraform workflows. As documented on the [setup-tflint](https://github.com/terraform-linters/setup-tflint) GitHub Action documentation:

```yaml
- uses: terraform-linters/setup-tflint@v5
- uses: terraform-linters/tflint-load-config-action@v1
  with:
    source-repo: thetestlabs/tflint-config
- run: tflint -f compact
```
