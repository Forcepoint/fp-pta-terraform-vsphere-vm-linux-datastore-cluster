# vsphere-vm-linux-datastore-cluster Terraform Module

This contains an abstracted resource for creating a virtual machine with a Linux OS
on a datastore cluster instead of a specific datastore. See https://www.terraform.io/docs/providers/vsphere/r/virtual_machine.html

See the [variables.tf](variables.tf) file for descriptions of each variable. If default is not listed,
the variable is required. If a default is null, Terraform behaves as though you had completely 
omitted it.

Minimum Terraform Version: 0.12

For information about PTA and how to use it with this Terraform module please visit https://github.com/Forcepoint/fp-pta-overview/blob/master/README.md