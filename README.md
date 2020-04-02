# Single Node QEMU/KVM Fedora CoreOS Rocket.chat

## Quickstart

```
# Install pip3 and git
sudo dnf install -y python3-pip git

# Clone playbooks
git clone --recurse-submodules https://github.com/nccurry/fcos-rocketchat
cd fcos-rocketchat

# Install ansible
pip3 install ansible --user

# Deploy Rocket.chat
./playbooks/main.yml -v
```

## Architecture
https://www.redhat.com/sysadmin/podman-shareable-systemd-services
https://github.com/nccurry/libvirt_coreos_vm