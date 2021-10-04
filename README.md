# tf-template

<!--- BEGIN_TF_DOCS --->
## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_terraform"></a> [terraform](#requirement\_terraform) | >= 1.0 |

## Providers

No providers.

## Modules

No modules.

## Resources

No resources.

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_api_authorized_ips"></a> [api\_authorized\_ips](#input\_api\_authorized\_ips) | Restricts access to specified IP address ranges to access Kubernetes servers | `list(any)` | `[]` | no |
| <a name="input_email"></a> [email](#input\_email) | Email address for alerts | `string` | `"root@localhost"` | no |

## Outputs

No outputs.

<!--- END_TF_DOCS --->
