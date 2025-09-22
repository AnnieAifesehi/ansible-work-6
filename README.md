# ansible-work-6

This repository contains a set of example Ansible playbooks and static pages used for demos.

Quick examples:

- Run the single-play example against group `g1`:

	ansible-playbook -i hosts.ini 01-single-play.yml

- Render and deploy the dynamic template:

	ansible-playbook -i hosts.ini 10-dynamic.yml
