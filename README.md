# ansible-ec2spinup
This playbook will create a security group with ssh port open and spin up an Ec2 instance. 

##Prerequisites


#1.Install Ansible on a linux machine and setup it as Ansible-master(I have setup in my local linux machine)
#2.Install Python boto library
#3.Create an IAM Role with ec2fullaccess policy and configure the user in the ansible master machine



### vars_files:
aws_keys.yml\
  aws_access_key:\
  aws_secret_key:
	


