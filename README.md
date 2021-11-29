### Building with AWS ECS part 2

This is the code from part 2 of the [“building with AWS ECS“ series](https://www.jerrychang.ca/writing/introducing-aws-ecs-technical-series).

### Getting started

#### Setting up infrastructure

```sh
export AWS_ACCESS_KEY_ID=<your-key>
export AWS_SECRET_ACCESS_KEY=<your-secret>
export AWS_DEFAULT_REGION=us-east-1

terraform init
terraform plan
terraform apply -auto-approve
```
