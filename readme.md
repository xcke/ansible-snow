# Connecting ServiceNow to Ansible Tower
1. Get the API from <tower_host>/api. 
2. Create a new REST Message in Service Now. (Assuming OAUTH profile between ServiceNow & Tower already created)
3. Add in the Header: Content-Type: application/json
4. In the body, the ansible extra vars
5. Create a new workflow Requested Item [sc_req_item] and copy paste the script 4. provides. 
6. add script to ref values
