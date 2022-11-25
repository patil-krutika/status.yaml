# status.yaml
---
- name: check status
  hosts: 10.0.3.15
  tasks:
    - name: check services
      command: automation-controller-services status
