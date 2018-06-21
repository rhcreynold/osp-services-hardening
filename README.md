# osp-services-hardening

This is a shot-gun approach of securing the RHOSP services based on the hardening guide.

It may or may not work, after running the playbook you need to restart all services/containers or just reboot all the things.

To run:

`ansible-playbook -i /usr/bin/tripleo-ansible-inventory main.yml`
