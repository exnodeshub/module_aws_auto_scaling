# module_aws_vpc  
My module vpc aws

## Getting started  
config git credentical for private repo   
href: https://gitlab.com/exnodes-new/terraform-core/-/tree/master/modules/module_aws_auto_scaling?ref_type=heads

add module    
example:       
```JavaScript

module "ims-service-auto-scaling" {
  source = "./modules/auto-scaling"
  ecs_cluster = "your ecs cluster"
  ecs_service = "your ecs service"
}
```

# Input 
```JavaScript
variable "ecs_cluster" {}
variable "ecs_service" {}

```

# Output 
```JavaScript

```