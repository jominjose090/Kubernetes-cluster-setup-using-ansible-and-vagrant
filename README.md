Kubernetes cluster setup using Ansible and Vagrant

Hello there! This project was created for Kubernetes cluster installation with Vagrant Vms, everything is installed using Ansible.

1. Installation consists of One Master node and 2 worker nodes.
2. Use included Vagrant file for creating VMs
3. After the VMs are ready make it ansible ready and using clone the repo and execute the playbook main.yaml, the role based playbook will help you install the cluster
4. Verify the installation using kubectl cluster-info && kubectl get nodes
