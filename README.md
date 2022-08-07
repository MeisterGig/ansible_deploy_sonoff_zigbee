![Ansible Linter](https://github.com/MeisterGig/ansible_deploy_sonoff_zigbee/actions/workflows/ansible-lint.yml)

Ansible Playbook for installation of Zigbee2MQTT, Homeassistant ans Mosquitto.

## Requirements
You need to install ansible
``` bash
pip install ansible
```

## Execute Playbook
Run the Playbook with the following command:
``` bash
ansible-playbook -i inventory.ini create_panel_file.yml
```