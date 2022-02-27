playbooks
=========

For laptop setup

## Setup

### Get [Ansible](https://www.ansible.com/)

curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
python3 get-pip.py --user
python3 -m pip install --user ansible
export PATH=/Users/benny/Library/Python/3.8/bin:$PATH
```
### Set up a virtual env

```
python3 -m virtualenv ansible
python3 -m pip install virtualenv
virtualenv ansible
source ansible/bin/activate
```
### Run the playbook!
```
ansible-playbook playbook.yml
```
