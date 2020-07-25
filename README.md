Description:
------------
This simple role i use to install and prepare my windows 10 ambient.

Requirements:
------------
- Ansible only works on linux, so the environment needs to have an active wsl.
- In the installation [folder](https://github.com/duranlopes/ansible-windows10/tree/master/setup) are the powershell scripts needed to activate winrm. Remembering to run them in administrator mode.

How to use:
-----------
ansible-playbook -i hosts playbook.yml -u <Admin> -k 

[Ansible Windows documentation](https://docs.ansible.com/ansible/latest/user_guide/windows_setup.html)
