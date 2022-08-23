# Terraform AWS Output Utility
- Provide some common output used when creating other resources (for exp: alias abbreviation for AWS resources (Internet gateway => IGW) )
```Bash
module "aws-utils"{
    source = "git::https://github.com/Bao-Truong/terraform-aws-output-util?ref=master"    
}
```

## From other resource use
> alias = module.aws-utils.alias["ec2"]

