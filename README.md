wireguard
=================

your description

OS Platform
-----------------

### Debian

- bookworm
- bullseye

Role Variables
--------------

### [defaults/main.yml](defaults/main.yml)

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードなどを参照してください。

#### `wireguard_version`

インストールするバージョン

#### `wireguard_packages`

インストールするパッケージ

### [vars/main.yml](vars/main.yml)

設定値については[vars/main.yml](vars/main.yml)を参照してください。

#### `wireguard_dependency_packages`

#### `wireguard_home`

#### `wireguard_user`

#### `wireguard_group`

Example Playbook
--------------

```yaml
- hosts: servers
  roles:
    - role: wireguard
```

License
--------------

Apache License 2.0
