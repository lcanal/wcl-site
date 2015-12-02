# wcl-site
WestCoastLabs Infrastructure Layout and Ansible Scripts

This layout will start to depend on docker nodes, and treat servers as independent nodes to use at will. Will gradually start to move infrastructure at home to a container based infra.


Note:

Will at some point start to move to hybrid cloud infrastructure.
Un-deployment still in process, still working on new field deployment dependency.
 

`Dependant Variables`

Environment Variables:

VMWARE_USER

VMWARE_PASS

VMWARE_HOST

`Assumptions`

For now we'll need a working cobbler server with a default profile and root ssh-keys

===
Cobbler

Make sure cobbler has a mounted DVD on its filesystem via the command:

'mount -t iso9660 -o loop,ro /var/ISOs/CentOS-6.6-x86_64-bin-DVD1.iso /mnt/CentOS6.6/'


and that you have a system pxeimage labeled 'default'
