### RoR stack installation in one go..

Change the variables in group_vars/all and add the host in hosts file and you are good to go.
Host file should have the following structure:
```
[servers]
ip-here ansible_connection=ssh  ansible_user=ubuntu ansible_python_interpreter=/usr/bin/python3
```

## TODO:
  1. Postgres Installation and Configuration.
  2. Ganglia Integration.
