# event-driven-cluster-scaling
Ansible EDA to manage location and scale of OpenShfit workloads


## For Playbooks
Need to create an [ansible.cfg](https://access.redhat.com/documentation/en-us/red_hat_ansible_automation_platform/1.2/html/getting_started_with_red_hat_ansible_automation_hub/proc-configure-automation-hub-server) with Automation Hub token and an `extra_vars.yml` file with these contents:
```yaml
--- 
xtra_openshift_admin_username: "cluster-admin"
xtra_openshift_admin_password: ""
xtra_openshift_api: ""
```
