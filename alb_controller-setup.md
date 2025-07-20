- Downloaded the IAM policy JSON for the AWS Load Balancer Controller directly from the official Kubernetes AWS GitHub repository.

- Created a new IAM policy in AWS named AWSLoadBalancerControllerIAMPolicy using the downloaded JSON document.

- Set up an IAM service account in the kube-system namespace using eksctl, and attached the above IAM policy to it.

- Made sure the service account was correctly associated with my EKS cluster and had the necessary permissions.

- Added the AWS EKS charts repository to Helm using:
  helm repo add eks https://aws.github.io/eks-charts

- Updated the Helm repository to get the latest chart versions.

- Installed the AWS Load Balancer Controller into the EKS cluster using Helm with the required parameters:
    Cluster name
    Service acc name
    Region
    VPC ID

- Set serviceAccount.create=false since I had already created and configured the IAM role manually.

- Verified that the ALB controller was successfully deployed:
  kubectl get deployment -n kube-system aws-load-balancer-controller

