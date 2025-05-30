# Terraform - provisioners

## Overview 
In this lab, you will update `main.tf` to include provisioners.

Provisioners allow you to run shell scripts on the local machine or remote resources. You can also use vendor provisioners from Chef, Puppet, and Salt.

## Add provisioners
This lab updates the `main.tf` in the `tf-lab2` directory. 

Add a `local-exec` provisioner with the following attributes: 
- command: Echo the public IP addresses into a file named `public_ips.txt`

Add another `local-exec` provisioner with the following attributes: 
- command: Echo the private IP addresses into a file named `private_ips.txt`



## Cleanup

Run the following to clean up the resources

```
terraform destroy -auto-approve
```



## Congratulations
