# 4lie Ansible Playbooks

For running this Ansible on Mac OS at first you should install `gnu-tar` using below command:

```
brew install gnu-tar
```

After install `gnu-tar`, you should run this Ansible using below commands:

```
ansible-galaxy install -r requirements.yaml

export OBJC_DISABLE_INITIALIZE_FORK_SAFETY=YES

ansible-playbook main.yaml
```
