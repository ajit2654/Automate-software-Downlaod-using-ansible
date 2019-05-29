# Automate-software-Downlaod-using-ansible
This is a simple ansible-playbook for learning purpose.
We can automate download of multiple software using this playbook.
As like you can install putty,rufus,vmware,wireshark,whatapps in windows as well as in linux.
I have used get_url module to fetch downloadable link from google or particular software and also work multiple software.
with_items modules works as a loop in playbook.
 
 To run this playbook first of all you need to install ansible.You can also go here for installation of ansible:
 https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html
 then run on terminal:
 ansible-playbook Download_software_putty.yml -vvv
 
