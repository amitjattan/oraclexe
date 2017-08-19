oraclexe
========

This will install Oracle Express (XE) using Ansible. There is a good Oracle repo for creating docker images [Oracle Database Docker Images](https://github.com/oracle/docker-images/tree/master/OracleDatabase/dockerfiles) that was used to model this role.

Requirements
------------

Using the following tools to develop:

- ansible
- virtualenv
- pip
- molecule
- docker


Role Variables
--------------

None at this time.


Dependencies
------------

There are no other Ansible module dependencies.


Example Playbook
----------------

See playbook.yml for examples.


Inital Setup
------------

This role was created using:

   ```molecule init --role oraclexe --driver docker```

Then the following commands were run:

    pip install ansible
    pip install molecule
    pip install docker
    molecule test


Development
-----------

* After the initial setup, to activate the python virtual environment run:

```source venv/bin/activate``` 



* To test, run:
 
 ```molecule test``` 
 


License
-------

BSD

Author Information
------------------

mike.kinney@gmail.com
