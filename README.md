✅ Security Setup

Created two Security Groups: one for the Ansible control node and one for the web servers.

Allowed SSH from IP and Ansible SG, and HTTP traffic to servers.

✅ Provisioning

Launched Amazon Linux 2 EC2 as the Ansible controller.

Generated and imported SSH keys for secure connections.

✅ Automation with Ansible

Installed Ansible on the control node.

Wrote an inventory file with private IPs of servers.

Created a simple playbook (deploy-techmax.yml) to install and start NGINX.

Verified reachability with ansible all -m ping.

✅ Efficiency

Configured ansible.cfg to avoid repeating SSH options.

🔧 Outcome: With a single command (ansible-playbook deploy-techmax.yml), I automated the full deployment of a web server environment on AWS.
