# Getting Started
- Update inventory.yaml with the machine(s) you wish to use
- Ensure that you have ssh keys for those machines
- run `ansible-playbook -i inventory.yaml install_gnuradio.yaml --ask-become`