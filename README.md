Ansible Role: Git
=========

Intsall git across different operating systems.

### Supported platforms:

|     Name    	|    Version    	|
|:-----------:	|:-------------:	|
| RHEL/CentOS 	|       8       	|
|    Fedora   	|       32      	|
|    Ubuntu   	| 20.04 [Focal] 	|
|  Archlinux  	|      all      	|
|   Windows   	|       10      	|
|    MacOS    	|     Mojave    	|

---

Requirements
------------

- On Windows `Chocolatey` must be installed
- On MacOS `Homebrew` must be installed

Example Playbook
----------------

```yml
- hosts: all
  roles:
    - git
```


License
-------

GPL

Author Information
------------------

Created by [theJaxon](https://github.com/theJaxon)