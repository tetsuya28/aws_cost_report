## What is aws_cost_usage
- Notify DAILY cost usage of an AWS account to slack channel.

## How to use this
- Init
```
cp .env{.sample,}
cp .terraform.tfvars{.sample,}
make init
```

- Run locally
```
make run
```

- Deploy to AWS with terraform
```
make plan
make apply
```
