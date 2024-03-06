Configuring:
- Jenkins, install-jenkins.yml playbook;
- Kubernetes cluster, install-k8s.yml playbook;
- Deploying java app code in Jenkins via building with Maven and pushing to dockerhub;
- Pulling the image from dockerhub using ansible and deploying in Kubernetes cluster using deployment.yml and service.yml files.

These were done on the 3 EC2 instances provisioned by terraform using following repo:
https://github.com/tch-do-23/Terraform_part.git
