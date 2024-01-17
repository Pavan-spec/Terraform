File is updated
Before run apply create .ssh using  ssh-keygen -t rsa
terraform pla
terraform apply
ssh -i MyKey.pem ubuntu@54.210.15.169
once you enter into server
run minikube version command you will see minikube installed
run : minikube start - to start minukebe cluster
run : minikube start --memory=4096 --driver=hyperkit - when you use advance lever k8s

Kubernetes cheat sheet - To see all k8s commands 
https://kubernetes.io/docs/reference/kubectl/quick-reference/

Ref: for setting up minikube on ec2 using terraform 
https://github.com/ranjit4github/terraform-ec2-minikube/blob/master/ec2.tf
