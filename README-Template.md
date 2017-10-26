# Project Title

The project contains Ansible playbook to automate creation of AWS VPC infrastructure in order to develop machine learning solutions while ensuring data privacy.

## Getting Started
Clone the repository to your local machine

### Prerequisites
Since it is an ansible script and uses awscli in order to set up components of VPC such as NAT gateway, you need to install following to your local machine:

```
pip install ansible
pip install boto
pip install awscli
```

### Configuring the playbook

1.Update the vars.yml file and change variable accordingly, depending on the use case of your organization.
2.Since ansible uses python interpreter, provide the right path to your python interpreter in local machine inside inventory file.



## Running the tests

Switch to the directory where you cloned the repository and then enter the command:

```
ansible-playbook playbook.yml –i inventory –e @vars.yml
```
## Built With

* [Ansible](http://docs.ansible.com/ansible/latest/guide_aws.html) - Ansible automation tool
* [AWSCLI](https://aws.amazon.com/cli/) - Amazon Web Services command line interface


## Acknowledgments
https://blog.scottlowe.org/2015/11/21/using-ssh-bastion-host/

https://blog.scottlowe.org/2017/05/26/bastion-hosts-custom-ssh-configs/

http://tenmilesquare.com/using-ssh-through-a-bastion-host-transparently/


