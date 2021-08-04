# ansible-role-sosreport-gather

**This ansible role is to install, run and collect sosreports.**


## Installation

To install the role, create `requirements.yaml` with this content:

    - name: sosreport_gather
      src: https://github.com/jhutar/ansible-role-sosreport-gather.git
      version: origin/main

and then to install the role:

    ansible-galaxy install -r requirements.yaml --roles-path roles/

Now the role is available in `roles/sosreport_gather/`.

Check `sosreport_gather.yaml` for example on how to run the playbook.


## Configuration


### Default variables


## References

1. To read more about sosreport
  - https://access.redhat.com/solutions/3592
