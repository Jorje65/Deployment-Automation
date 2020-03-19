# Deployment-Automation

1.	Write a vagrant script to deploy a Kubernetes cluster with 3 nodes in virtual machines (can use any supported hypervisor, suggest VirtualBox)
2.	Deploy any web application onto that cluster. The web application should be accessible from your web browser
3.	Create a CI/CD pipeline that deploys the web application onto the cluster.

Step 1: Creating a Vagrantfile
Using the text editor of choice create a file with named Vagrantfile, inserting the code below. The value of N denotes the number of nodes present in the cluster, it can be modified accordingly. In the below example, we are setting the value of N as 2.

Step 2: Create an Ansible playbook for Kubernetes master.
Create a directory named kubernetes-setup in the same directory as the Vagrantfile. Create two files named master-playbook.yml and node-playbook.yml in the directory kubernetes-setup.

Step 3: Upon completing the Vagrantfile and playbooks 
$vagrant up

Step 4: Deploy web application on the newly created kubernetes cluster







