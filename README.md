ocp-ansible-playbooks
================

### Utility ansible playbooks to automate Openshift Container Platform (OCP) hosts preparation

1. Generate ansible inventory file for Openshift Container Platform installer

1.1 Openshift on AWS 

1.1.1 Edit ocp_inventory_template_aws.yml

1.1.2 ansible-playbook inventory_template_aws.yml
 
1.2 Openshift on Azure

1.2.1 Edit ocp_inventory_template_azure.yml

1.2.2 ansible-playbook inventory_template_azure.yml

1.3 Openshift on Openstack      
 
1.3.1 Edit ocp_inventory_template_osp.yml

1.3.2 ansible-playbook inventory_template_osp.yml

1.4 Openshift on physical or virtual hosts

1.4.1 Edit ocp_inventory_template.yml

1.4.2 ansible-playbook inventory_template.yml

2. Prepare hosts for Openshift Container Platform installation

2.1 Edit ocp_node_setup.yml

2.2 ansible-playbook ocp_node_setup.yml

3. Install Openshift Local

3.1 ansible-playbook ocp_local_setup.yml

