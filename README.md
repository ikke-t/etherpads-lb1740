Etherpads-lb1740
================

This role sets up etherpad pages for Event Driven Ansible escape room.
Etherpad is used to set up team communications for event, along with
instructions for competitors.

Requirements
------------

This is originally done for LB1740, lab for Red Hat Summit 2024 and later
workshop based on it.

Role Variables
--------------

Role variables come mainly from AgnosticD/AgnosticV, so that it can be used
along the automated lab setup from demo.redhat.com.

<https://github.com/rhpds/agnosticv/tree/master/summit-2024/SMT_LB1740_EDA_DYNATRACE>
<https://github.com/redhat-cop/agnosticd/>

Dependencies
------------

Before the role is run, demo.redhat.com has already built us etherpad on top of
OpenShift.

Example Playbook
----------------

    - hosts: localhost
      roles:
         - etherpads-lb1740

License
-------

BSD

Author Information
------------------

Ilkka Tengvall <itengval@redhat.com>
