# Deploy Jenkins on RHEL host

## Use case
I need to deploy Jenkins on a remote RHEL host that sits on a private network behind a bastion I can reach from my laptop. The Ansible playbook included
in this repo will deploy everything needed to get Jenkins working. Customizes it to your specific needs as you like. 

The image below depicts the network topology addressed with this solution: 


## To run
`ansible-playbook -i inventory.txt main.yaml` from your laptop
