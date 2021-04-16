# Ansible-Install-Cloudwatch-Agent

This script would install Cloudwatch agent on Windows Servers.

If your Windows is not already configured, you would need to download a powershell script and run it. If you're spinning up a new VM, you may want to run a bootstrap script to run the powershell script for you.

Link to ps script : 
https://raw.githubusercontent.com/ansible/ansible/devel/examples/scripts/ConfigureRemotingForAnsible.ps1

To run the playbook, add the hosts to the hosts file and then just run the following :

ansible-playbook -i hosts playbook.yml
