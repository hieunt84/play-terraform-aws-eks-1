### Ref
https://medium.com/devops-mojo/terraform-provision-amazon-eks-cluster-using-terraform-deploy-create-aws-eks-kubernetes-cluster-tf-4134ab22c594


### resource aws
1/vpc
https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/vpc

2/subnet
https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/subnet


### Function in Terrafor

1/flatten
https://www.terraform.io/language/functions/flatten

2/merge
https://www.terraform.io/language/functions/merge

### Data souce
https://stackoverflow.com/questions/47721602/how-are-data-sources-used-in-terraform
https://www.terraform.io/language/data-sources

```
The main difference between Terraform data source, resource and variable is :

Resource: Provisioning of resources/infra on our platform. Create, Update and delete!

Variable Provides predefined values as variables on our IAC. Used by resource for provisioning.

Data Source: Fetch values from our infra/provider and and provides data for our resource to provision infra/resource.

Examples are well explained above :)
```
