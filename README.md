Docker
========

Installs Docker, creates docker group.

Installation
--------------

`ansible-galaxy install alekseenkoss77.docker`

Role Variables
--------------

`defaults/main.yml`

| Name                        | Default Value |  Description    |
|-----------------------------|---------------|-----------------|
| docker_user                 | no            | user name will append to docker group |
| docker_group                | True          | create docker group |

Example Playbook
-------------------------
```yml
  - hosts: servers
    roles:
       - alekseenkoss77.docker
```
