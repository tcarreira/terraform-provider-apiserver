---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "apiserver_person Data Source - terraform-provider-apiserver"
subcategory: ""
description: |-
  Person data source
---

# apiserver_person (Data Source)

Person data source

## Example Usage

```terraform
data "apiserver_person" "example" {
  id = "0"
}
```

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- `id` (String) Person identifier

### Read-Only

- `age` (Number) Person age
- `description` (String) Person description
- `name` (String) Person name

