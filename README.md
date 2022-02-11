ansible-nvidia-container
=======

Ansible role to install the NVIDIA Container toolkit as described in the [NVIDIA Container Toolkit Guide](https://github.com/NVIDIA/nvidia-docker) in a RedHat/CentOS system.

Requirements
------------
Ansible >= 2.11


Usage
-----

```bash
$ ansible-galaxy install usegalaxy_eu.nvidia_container
```

And add it to your playbook's roles:

```yaml
- hosts: yourhost

  roles:
    - role: usegalaxy_eu.nvidia_container
      become: yes
```

License
-------

GPLv3

Author Information
------------------

[Gianmauro Cuccuru](https://github.com/gmauro)
