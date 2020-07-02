# DynamoDB IAM Policy Module

Use this module to generate IAM policies for DynamoDB access

Usage: 

```
module "policy" {
    name = "name"
    description = "blahblah"
    db_arn = "arn:..."
}
```