# AWS-EKS-Infrastructure-Deployment-with-Terraform-and-Application-Deployment
    # Terraform Module: EKS ClusterThis Terraform module creates an Amazon EKS (Elastic Kubernetes Service) cluster with managed node groups.

## Requirements

*   Terraform version 0.12 or later.
*   Amazon Web Services (AWS) account.

## Inputs

*   `cluster_name`: The name of the EKS cluster.
*   `cluster_version`: The desired Kubernetes version for the cluster.
*   `subnet_ids`: The list of private subnet IDs where the EKS cluster will be deployed.
*   `vpc_id`: The ID of the VPC where the EKS cluster will be deployed.
*   `tags`: A map of tags to assign to all resources created by the module.
*   `eks_managed_node_groups`: A map of managed node groups for the EKS cluster.

## Outputs

*   `cluster_id`: The ID of the created EKS cluster.
*   `cluster_name`: The name of the created EKS cluster.
*   `cluster_endpoint`: The endpoint for the created EKS cluster.

## More Information

For more information on AWS EKS and the options available, consult the [official AWS documentation](https://aws.amazon.com/eks/).

    Please note that this is just a template and you may need to tailor it to your specific requirements. Additionally, make sure you have the necessary permissions and configurations in place to run Terraform scripts.Hope this helps!
