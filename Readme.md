## AKS with Terraform

https://learn.microsoft.com/en-us/azure/developer/terraform/create-k8s-cluster-with-tf-and-aks

Access the master
	• echo "$(terraform output kube_config)" > ./azurek8s
	• export KUBECONFIG=./azurek8s
        * kubectl get nodes


