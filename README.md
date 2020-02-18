ansible-nvidia-container
=======

Ansible role to install the NVIDIA Container toolkit as described in the [NVIDIA Container Toolkit Guide](https://github.com/NVIDIA/nvidia-docker) in a Redhat/CentOS system.

Requirements
------------
Ansible >= 2.8



Usage
-----
Clone this repo into your roles directory:

```bash
$ git clone https://github.com/usegalaxy-eu/ansible-nvidia-container.git roles/nvidia-container
```

And add it to your playbook's roles:

```yaml
- hosts: yourhost

  roles:
    - role: nvidia-container
      become: yes
```

This role comes preloaded with multiple available defaults. You can override each one in your hosts/group vars, in your inventory, or in your play. See the annotated defaults in defaults/main.yml for help in configuration.
      
License
-------

GPLv3

Author Information
------------------

[Gianmauro Cuccuru](https://github.com/gmauro)
