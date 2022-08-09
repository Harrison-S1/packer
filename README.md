# Packer
Packer images using in the lab

**NOTE**
Yes there is a credentials.pkr.hcl there to use for ease of use with Proxmox. NO you would NEVER use it in production enviroment, it is for a lab enviroment only. 

## Before deployment
Run a validate to check for errors

```packer validate -var-file='./credentials.pkr.hcl' ./ubuntu-20.04.pkr.hcl```

## Build image example
```packer build -var-file='./credentials.pkr.hcl' ./ubuntu-20.04.pkr.hcl```
