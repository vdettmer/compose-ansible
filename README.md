Update docker host
=========

Simple Ansible role to update a Debian based docker host. E.g. ODROID in homelab.
All logic happens in tasks/main.yml
Containers will be updated if an automatic cron job pulls regularly and a rolling tag like latest or stable is used in the compose.yml