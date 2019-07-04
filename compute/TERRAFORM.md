## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-----:|:-----:|
| ansible-management-sg |  | string | n/a | yes |
| elb-sg |  | string | n/a | yes |
| elb\_healthy\_threshold |  | string | n/a | yes |
| elb\_unhealthy\_threshold |  | string | n/a | yes |
| instance-count |  | string | n/a | yes |
| instance-sg |  | string | n/a | yes |
| private\_subnets |  | list | n/a | yes |
| public\_key |  | string | n/a | yes |
| public\_subnets |  | list | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| elb-endpoint |  |

