sbog/haproxy
============

Role to install and configure HAProxy.

#### Requirements

Ansible 2.7+

#### Role Variables

For full list of variables look to `defaults/main.yml` file.

#### Dependencies

None

#### Example Playbook

```yaml
- name: Install HAProxy
  hosts: haproxies
  remote_user: root
  sudo: yes
  roles:
    - haproxy
```

#### License

Apache 2.0

#### Author Information

Stanislaw Bogatkin (https://sbog.ru)
