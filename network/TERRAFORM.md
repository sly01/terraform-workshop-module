## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-----:|:-----:|
| cidr\_block |  | string | n/a | yes |
| private\_cidrs |  | list | n/a | yes |
| private\_subnet\_count |  | string | n/a | yes |
| public\_cidrs |  | list | n/a | yes |
| public\_subnet\_count |  | string | n/a | yes |

## Outputs

| Name | Description |
|------|-------------|
| ansible-management-sg |  |
| elb-sg |  |
| elb-to-ec2 |  |
| private\_subnets |  |
| public\_subnets |  |

