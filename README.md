# MongoDB Cluster Ansible Playbook

This repository contains an Ansible playbook to set up and manage a MongoDB cluster.

## Prerequisites

1. Ensure you have Ansible installed on your control node.
2. Set up the inventory file (`inventory.yaml`) with your target hosts.

## Commands to Run the Playbook

To execute the playbook, use the following command:

```bash
export ANSIBLE_HOST_KEY_CHECKING=False
ansible-playbook -i inventory.yaml main.yml
```

## License

This project is open-source and licensed under the MIT License.