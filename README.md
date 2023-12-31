# ansible-local-configs

### Pihole

using [./playbooks/pihole.yaml](./playbooks/pihole.yaml) we deploy pihole in a podman container

#TODO: Make this rootless, I think it can be done pretty straightforward doing something with

- https://blog.christophersmart.com/2019/09/20/running-a-non-root-container-on-fedora-with-podman-and-systemd/
- https://linuxhandbook.com/rootless-podman/#want-to-bind-ports-less-than-1024
- https://mcastelino.medium.com/slirp4netns-how-does-it-work-5c0bd31200ce
- https://linuxhandbook.com/rootless-podman/



### Bhyve

#TODO:

Look at https://www.bsdstore.ru/en/about.html
Look at https://github.com/churchers/vm-bhyve
Follow along with https://productionwithscissors.run/2020/12/26/adventures-in-freebernetes-tutorial-build-your-own-bare-vm-k3s-cluster/ potentially?
