# expense-ansible-roles
Ansible Roles 
a proper structure of plabook that includes variables, files, templates, other dependensies, handlers, etc. we can reuse roles

tasks/ --> you can keep all your tasks here
handlers/ --> you can keep all your tasks here
templates/ --> you can all your files with variables here
files/ --> files without variagbles here
vars/ --> low priority variables 
meta/ --> other dependencies
library/ --> you can keep your custome modules using python here 
module_utils/ --> roles can also include custom module_utils
defaults/ --> high priority variables
tests/ --> you can keep your test files here
README.md --> you can keep your role documentation here
LICENSE --> you can keep license information here
AUTHOR --> you can keep author information here
CHANGELOG.md --> you can keep changelog information here
CONTRIBUTING.md --> you can keep contribution guidelines here
CODE_OF_CONDUCT.md --> you can keep code of conduct information here
.gitignore --> you can keep files and directories to be ignored by git here
.playbook.yml --> you can keep sample playbook to test the role here
meta/main.yml --> you can keep role dependencies here
lookup_plugins
# Ansible Role: expense-ansible-roles
This Ansible role sets up and configures expense management applications. 




ansible.cfg

/etc/ansible/ansible.cfg

1. ANSIBLE_CONFIG (Environment variable if set)

default- - - - - > > > /etc/ansible/ansible.cfg

change ansible.cfg to desired location
export ANSIBLE_CONFIG=/home/ec2-user/expense-ansible-roles/ansible.cfg
echo $ANSIBLE_CONFIG
unset ANSIBLE_CONFIG


2. CURRENT WORKING DIRECTORY
3. HOME DIRECTORY
4. etc forlder