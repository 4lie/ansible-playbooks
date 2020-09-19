# 4lie Ansible Playbooks Example

## Introduction

Charlie Ansible Playbooks example.

## Installation

For running this Ansible on Mac OS at first you should install `gnu-tar` using below command:

```
brew install gnu-tar
```

After install `gnu-tar`, you should run this Ansible using below commands:

```
export OBJC_DISABLE_INITIALIZE_FORK_SAFETY=YES

ansible-galaxy install -r requirements.yaml

ansible-playbook main.yaml --tags all
```
