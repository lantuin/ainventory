A simple ansible playbook to retrieve a complete software asset inventory from your environment.
It's compatible with Linux (Debian and Red Hat based), MAC (using system_profiler) and Windows (winRM protocol).

HOSTS file is self-explanatory. 

Output files will be written in inventory/ subdirectory


```
$ ansible-playbook playbook.yml -i hosts
```
