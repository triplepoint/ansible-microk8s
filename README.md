# Intro
This role installs and configures the Microk8s Kubernetes service, suitable for building
a test VM or appliance machine.

## Requirements
None

## Role Variables
See the [comment in the default variables file](defaults/main.yml) for information on configuration.

## Dependencies
None.

## Example Playbook
    - hosts: whatever
      roles:
        - triplepoint.microk8s

## License
MIT
