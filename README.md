# Preconfigured instances using multipass

Creates a new instance based on Ubuntu 20.04 LTS:

multipass launch focal -n play -c 2 -m 4G -d 10G --cloud-init cloud-init-1.yaml

multipass launch focal -n play -c 2 -m 4G -d 10G --cloud-init cloud-init-2.yaml

multipass launch focal -n play -c 2 -m 4G -d 10G --cloud-init cloud-init-play.yaml
