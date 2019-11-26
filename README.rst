ansible-collection-failure
--------------------------

To reproduce::

    ansible-galaxy collection build failure
    ansible-galaxy collection install mwhahaha-failure-1.0.0.tar.gz
    ansible-playbook sigh.yml
