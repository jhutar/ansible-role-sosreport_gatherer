# ansible-role-sosreport_gatherer

**This ansible role is to install, run and collect sosreports.**


## Installation

To install the role, create `requirements.yaml` with this content:

    - name: sosreport_gatherer
      src: https://github.com/jhutar/ansible-role-sosreport_gatherer.git
      version: origin/main

and then to install the role:

    ansible-galaxy install -r requirements.yaml --roles-path roles/

Now the role is available in `roles/sosreport_gatherer/`.

Check `sosreport_gatherer.yaml` for example on how to use the role in the playbook.


## Configuration

* To specify directory (local on Ansible controller) where you want to store the sosreport tarballs, use `sosreport_gatherer_local_dir` variable.


### Default variables

* `sosreport_gatherer_local_dir` set to `/tmp/sosreports/` by default

## References

1. To read more about sosreport
  - https://access.redhat.com/solutions/3592
