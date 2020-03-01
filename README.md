# puppet-devops-setup

A tutorial and example with 'Puppet'

## Example

```
puppet parser validate ntp.pp

su root

puppet apply ntp.pp --noop

puppet apply ntp.pp

ls -lrt /etc/ntp.conf

systemctl status ntpd	
```