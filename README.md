# do22-playbooks

Ensure that the ip inside the hosts file is the correct one. (vm1 for example)  \
To test playbooks in this repo, do: \
`cd /vagrant` \
`vagrant up` \
Check that you can ssh into vm1 by running: `vagrant ssh vm1`. \
After that, run `vagrant ssh-config >> ~/.ssh/config` to append the ssh config into your home folder's config, this will enable ansible to run playbooks on this machine.

Install the components with `run_app_locally.yml` playbook.
