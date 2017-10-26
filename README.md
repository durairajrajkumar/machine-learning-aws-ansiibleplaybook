# AWS_AnsiblePlaybook_MLResearch

<snippet>
  <content><![CDATA[
# ${1:Automating creation of Virtual Private Cloud in Amazon Web Services}
Virtual Private Cloud allows organisations to define their own virtual network, with customized security protocols and 
access control. SAP ML Research team worked on creating ansible scripts that enable you to create an infrastructure in which you can 
develop machine learning solutions, along with ensuring data privacy.
## Installation
Automation is done using ansible tool
1. Ansible : `sudo pip install ansible`
Some tasks require boto to be installed.
2.Boto : `sudo pip install boto`
NAT Gateway is installed using awscli in ansible playbook. You can use NAT Gateway module which is available now in ansible as well.
3.AWS CLI : `sudo pip install awscli`

## Use-cases
-Store your data within private subnet in order to ensure end-user privacy
-Launch instances within private subnet of VPC if you want to train a machine learning model.
## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D
## Credits

]]></content>
  <tabTrigger>readme</tabTrigger>
</snippet>
