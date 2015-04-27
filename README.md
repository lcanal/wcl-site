# wcl-site
WestCoastLabs Infrastructure Layout and Ansible Scripts

`Dependant Variables`

Environment Variables:

VMWARE_USER

VMWARE_PASS

VMWARE_HOST

`Assumptions`

For now we'll need a working cobbler server with a default profile and root ssh-keys

===Cobbler

Make sure cobbler has a mounted DVD on its filesystem via the command:

'mount -t iso9660 -o loop,ro /var/ISOs/CentOS-6.6-x86_64-bin-DVD1.iso /mnt/CentOS6.6/'


and that you have a system pxeimage labeled 'default'
