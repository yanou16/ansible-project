# Ansible Project
https://roadmap.sh/projects/configuration-management
This project is a basic Ansible setup to manage and configure remote servers.
<img width="1842" height="350" alt="image" src="https://github.com/user-attachments/assets/e6a47c40-dfa3-4f7f-9f2a-f81cdd49ea52" />
## Project Structure

- `inventory.ini` – Defines the target servers (hosts).
- `setup.yml` – Ansible playbook to configure the servers.
- Other configuration files can be added as the project grows.

## Requirements

- Ansible installed on your local machine or control node.
- SSH access to the target server(s).
- Proper SSH keys configured (`~/.ssh/authorized_keys` on the server).

## Usage

1. **Test connection to servers:**
   ```bash
   ansible -i inventory.ini myservers -m ping
``` 
