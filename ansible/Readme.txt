Ansible Kilo Installation on Ubuntu:

1. 1 node for ansible server and 3 nodes for openstack
2. group_vars folder has files where values need to be populated accordingly installation will be done
3. To setup environment on every node - env_setup.yml
4. To setup database, Rabbitmq, Keystone - kilo_keystone.yml
5. To setup glance - kilo_glance.yml
6. To setup nova components on controller node - kilo_nova.yml
7. To setup nova components on compute node - kilo_nova_compute.yml
8. To setup neutron controller components - kilo_neutron.yml
9. To setup neutron components on neutron node - kilo_neutron_network.yml
10. To setup neutron components on compute node - kilo_neutron_compute.yml
11. To setup cinder - kilo_cinder.yml
12. To setup horizon on controller - kilo_horizon.yml

