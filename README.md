# example-eks-oidc-iam-cloudformation

This repo contains:

1. An example CloudFormation template for the creation of an EKS compatible OpenID Connect provider
   using a CustomResource. 
   
   ```
   oidc-provider.yaml
   ```
   
   For full instructions, and how to test it, 
   see: https://bambooengineering.io/configuring-eks-for-iam-oidc-using-cloudformation/
   
1. Example files that show how to constrain EKS pod IAM roles, also just using CloudFormation.

   ```
   oidc-test-cloudformation.yaml
   oidc-test-kubernetes.yaml
   ```
   
   For a guide to accompany their use, see 
   https://bambooengineering.io/constraining-eks-pod-iam-roles-using-cloudformation/

