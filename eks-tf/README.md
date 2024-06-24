# EKS Managed Node Group Examples

Configuration in this directory creates Amazon EKS clusters with EKS Managed Node Groups demonstrating different configurations:


See the [AWS documentation](https://docs.aws.amazon.com/eks/latest/userguide/managed-node-groups.html) for additional details on Amazon EKS managed node groups.

The different cluster configuration examples provided are separated per file and independent of the other cluster configurations.

## Usage

To provision the provided configurations you need to execute:

```bash
$ terraform init
$ terraform plan
$ terraform apply --auto-approve
```
