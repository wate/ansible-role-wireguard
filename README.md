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

設定方法の詳細については[defaults/main.yml](defaults/main.yml)のサンプルコードを参照してください。

### `wireguard_version`

インストールするバージョン

### `wireguard_packages`

インストールするパッケージ

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
