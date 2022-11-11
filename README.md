# Terraform Provider Demo

Custom provider that contains a single "resource" and "data" source for the purpose of demonstrating private providers.

```
resource "demo_example" "example" {
  configurable_attribute = "some-value"
}
```

```
data "demo_example" "example" {
  configurable_attribute = "some-value"
}
```
