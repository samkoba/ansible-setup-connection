# ansible-setup-connection
 
To specify a user and password when connecting to a Windows host using Ansible, you can use the ansible_user and ansible_password variables in your inventory file.

Here's an example inventory file that specifies a group of Windows hosts with a user and password.

You can also specify the user and password in the ansible.cfg file, which allows you to specify these options globally for all playbooks. To do this, add the following lines to your ansible.cfg file