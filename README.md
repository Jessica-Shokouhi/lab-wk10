# Lab week 13

## Cole Kyle Jess

## Overview

This project uses Ansible with the aws_ec2 dynamic inventory to configure two AWS EC2 instances. The configuration was refactored into a playbook using roles for each server. The frontend server runs nginx and serves a simple HTML page.

### Commands needed to run the Ansible configuration

we looked at the flawed version of the ansible code and then made seperate role files and a improved .yml based off of it.

ran like this

```
ANSIBLE_CONFIG=./ansible.cfg ansible-playbook -i inventory/aws_ec2.yml playbook.yml

```

### server running on browser

![alt text](image2222.png)
