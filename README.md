# wordpress-with-ansible
Provisioning of AWS resources for a WordPress website can be done with the use of Ansible.
Before running the playbooks on EC2 instances, you need to install ansible on a control machine. I did so using a git repository 

$ git clone https://github.com/ansible/ansible.git

$ cd ./ansible

$ make rpm

$ sudo rpm -Uvh ./rpm-build/ansible-7.noarch.rpm

# WordPress database settings
wp_db_name: wordpress 
wp_db_user: wordpress
# Database password here 
wp_db_password: Ch@ng3m3!
