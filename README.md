# Private Registry AWS Webapp
This is an example module

## Usage
```hcl
module "webapp" {
  source     = "app.terraform.io..."
  version    = "x.x.x"
  public_key = "-----BEGIN PUBLIC KEY----- MIICIjANBgkqh..."
}

output "website_endpoint" {
  value = module.webapp.endpoint
}
```
