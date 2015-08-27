# InfluxDB Ansible Role

Installs and configures InfluxDB.

# Configuration Options

Name                   | Default | Description
-----------------------|---------|------------------------------------------------
influxdb_admin_enabled | True    | Enables the built-in, web-based admin interface

# Usage example

```yaml
---
- hosts: all
  sudo: true
  roles:
    - role: influxdb
      influxdb_admin_enabled: false
```

# License

[![GPLv3](http://www.gnu.org/graphics/gplv3-127x51.png)](http://www.gnu.org/licenses/gpl-3.0.html)

