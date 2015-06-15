# OpenSSL Update

Another bug in OpenSSL? Update the fleet in minutes with this Ansible playbook

Usage
------------------

Note: Since service names don't have a 1-1 mapping to process names, you will need to add your specific services to the ```openssl_dependants``` variable.

```shell
$ # Install Pip with your package manager
$ pip install ansible
$
$ # Setup your shell environment if you haven't done so already
$ eval `ssh-agent -s`
$ ssh-add id_rsa
$
$ # Deploy
$ ansible-playbook -i hosts.ini playbook.yml
```

TODO
------------------

  - [ ] Add support for RHEL based systems


License 
------------------

This project is licensed under the MIT license.

Author Information
------------------

Elliot Anderson ([Email](mailto:elliot.a@gmail.com), [Twitter](http://www.twitter.com/elliotanderson))