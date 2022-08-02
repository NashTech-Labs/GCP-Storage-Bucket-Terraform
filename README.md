### Create a Storage Bucket in GCP with Terraform

WE can create bucket in google cloud in following three ways:

1. Through Console
2. Through Gcloud Cli
3. IAC

we are using IAC (INfrastructure as a Code tool) to create buckets .

### Create Accompanying Files :

In this directory under storage-files I have created four files named as :

* main.tf
* provider.tf
* variable.tf
* terraform.tfvars


Once all of our files have been create , please run the following commands from the terminal.
, In order to Create a Storage Bucket in GCP using Terraform .



We have four main Terraform commands to use , they are as :

* terraform init
* terraform plan
* terraform apply
* terraforn destroy 



Let's see why these files are used:

**terraform init**

In order to initialise our working directory containing our terraform code.

**terraform plan**

It is used to preview our infrastructure prior to executing our terraform code.

**terraform apply**

It is used to apply all the changes specified in the plan into motion.

 
let's apply them all:


```
terraform init
```

```
terraform plan
```

```
terraform apply
```


Once you’ve confirmed that the resources were successfully created, in order to avoid unnecessary charges, ensure that all resources are destroyed.


This can be achieved by entering the Terraform destroy command in your terminal as :



**terraform deploy**
It is used in order to delete all the resources together.



```
terraform destroy
```
