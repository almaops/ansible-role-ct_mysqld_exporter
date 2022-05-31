# almaops.ct_mysqld_exporter
[![License](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg)](https://opensource.org/licenses/MIT)

# Role variables
Please refer to [defaults/main.yml](./defaults/main.yml) for full list of available variables. 

# Dependencies
None

# Example playbook
```
- hosts:
    - servers
  become: true
  roles:
    - role: almaops.ct_mysqld_exporter
      ct_mysqld_exporter_env_data_source_name: "user:pass@mysql_host:3306/db_name"
```

# License
[MIT](./LICENSE)

# Contributors
[Valentin Gostev](https://github.com/ussrlongbow)
