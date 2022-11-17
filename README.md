# InfluxDB 2.x role

example usage in playbook:

```
- name: SIOT server
  hosts: siot
  become: yes
  roles:
    - { role: influxdb2, tags: influxdb2 }
```
