# Sonatype Nexus Installation Playbook

This Ansible playbook installs Sonatype Nexus using Docker on a specified VM and configures it to use an external volume for persistent data storage.

## Prerequisites

1. **Ansible**: Ensure Ansible is installed on your local machine.
   - Installation: `sudo apt-get install ansible`

2. **Prepare the environment**:
   Ensure the SSH key environment variable is set:

   ```bash
   export SSH_PRIVATE_KEY_PATH="/path/to/your/sms-gatewaykey.pem"

3. **Run the playbook**:

   ```bash
   ansible-playbook -i hosts.yml install_caddy.yml
