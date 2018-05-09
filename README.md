# jsnapy

This repository provides a few example JSNAPy tests related to BGP/EVPN

Useful links:

Execute JSNAPy via Ansible:
http://junos-ansible-modules.readthedocs.io/en/2.0.2/juniper_junos_jsnapy.html

Writing JSNAPy tests:
https://github.com/Juniper/jsnapy/wiki/2.-Writing-test-and-config-file

Running JSNAPy tests via cmd line:
1. jsnapy --snap pre -f config_check.yml (for taking pre snapshot)
2. jsnapy --snap post -f config_check.yml (for taking post snapshot after some modification)
3. jsnapy --check pre post -f config_check.yml (compares pre post snapshot as per test cases)
4. jsnapy --diff pre post -f config_check.yml (compares pre post snapshot files, shows the diff in 2 Columns)
https://github.com/Juniper/jsnapy
