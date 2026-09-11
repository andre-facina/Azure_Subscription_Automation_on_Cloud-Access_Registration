#Ansible Playbook to automate the registration for multiple Azure subscriptions on the RH Cloud Access program.
# 
# This playbook was created based on the Red Hat solution: https://access.redhat.com/solutions/6964853
#
# HOW TO USE:
# 
# First, change the azure account in Azure_Account variables and insert the Azure ID for the subscription and a name.
#
# Run the playbook with the rh_api_token ansible-playbook -e "rh_api_token=TOKEN_HERE" playbook.yml
#
# The rh_api_token can generated in: https://access.redhat.com/management/api 

