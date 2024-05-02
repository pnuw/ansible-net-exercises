# README.md

Write playbooks to satisfy the following requirements. Use a host group named `poc_hosts` for all tasks below.

Also after writing each playbook, please answer the following questions. Put the answers as comments on top of the file. A comment in yaml starts with #:

1. How many times did you have to leave your VS Code environment to complete this task?
1. List all the sources you used to complete this task.
1. How long did it take to complete this task?

## Problem Set

### POC Network Admin Tasks (Low)

#### Connectivity Test

1. Name the playbook as `m_net_1.yml`
1. Use a module to verify connectivity to a Cisco IOS device.
1. Use the `ping` module to accomplish this.

### POC Network Admin Tasks (Medium)

#### Device Information

1. Name the playbook as `m_net_2.yml`
1. Collect Ansible facts about a Cisco IOS switch
1. Collect only the interfaces' resource facts and no legacy facts

#### BGP Management

1. Name the playbook as `m_net_3.yml`
1. Configure BGP neighbors
1. Use 199.0.99.10 & 64.5.2.15
1. Use address family mode

### POC Network Admin Tasks (complex)

#### F5 BIGIP Load Balancer Management

1. Name the playbook as `m_net_4.yml`
1. Complete all tasks in the same playbook
1. Shut down all non-management interfaces
1. Check the status of the management VLAN
1. Turn the non-management interfaces back on
