# Packer
Packer images using in the lab

## Before deployment
Run a validate to check for errors

```packer validate -var-file='./credentials.pkr.hcl' ./ubuntu-20.04.pkr.hcl```

## Build image example
```packer build -var-file='./credentials.pkr.hcl' ./ubuntu-20.04.pkr.hcl```