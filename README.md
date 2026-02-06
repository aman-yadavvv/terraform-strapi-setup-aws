
## STRUCTURE

```text
.
├── modules/
│   ├── ami/             
│   ├── ec2/             
│   ├── keypair/         
│   ├── load-balancer/   
│   ├── networking/       
│   └── security-group/  
└── terraform/
    ├── main.tf
    ├── variables.tf
    ├── outputs.tf
    ├── provider.tf
    ├── terraform.tfvars
    ├── .terraform.lock.hcl
    └── user_data.sh     
```


Run `terraform apply --auto-approve`, wait ~20 mins, and open the URL in your browser — Strapi will appears!


🚀 Done! Your Strapi instance is live.
