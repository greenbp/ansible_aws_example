Anisble 2.3 playbook to deploy 5 nginx ec2 instances and add them to an elb

Requirements:
Add your access_key and secret_key to top of file and point ansible_ssh_private_key_file to your aws ssh key
Allow port 80 to your instances to pass health checks

To run:
	`ANSIBLE_HOST_KEY_CHECKING=false ansible-playbook site.yml`

See sample.log for an example run that resulted in web-lb-1070693179.us-east-1.elb.amazonaws.com
