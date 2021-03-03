# AWS API Spreadsheet Terraform module

Terraform module which creates a Lambda with a ready-to-use NodeJS source code to handle
XLSX (and other) spreadsheet generation on AWS.

## Usage

```hcl
module "lambda-api-spreadsheet" {
  source = "genstackio/layer-api-spreadsheet/aws//modules/lambda"

  name   = "my-lambda-api-spreadsheet"
}
```
