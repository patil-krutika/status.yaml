# status.yaml
---
- name: check status
  hosts: 10.0.3.15
  state: present
  tasks:
    - name: check services
      command: automation-controller-services status
