---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "eveng Provider"
subcategory: ""
description: |-
  
---

# eveng Provider



## Example Usage

```terraform
provider "eveng" {
  host     = "http://localhost"
  username = "admin"
  password = "eve"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Optional

- `host` (String) The host of the Eveng API. (Can also be set with the EVE_HOST environment variable)
- `password` (String, Sensitive) The password for the Eveng API. (Can also be set with the EVE_PASSWORD environment variable)
- `username` (String) The username for the Eveng API. (Can also be set with the EVE_USER environment variable)
