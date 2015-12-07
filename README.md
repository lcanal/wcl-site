# wcl-site
WestCoastLabs Infrastructure Layout and Ansible Scripts

Infrastructure will be based on DigitalOcean backed CoreOS hosts that will have docker installed. If doing a completely greenfield install, use do-provision.yml in order to create the necessary droplets. 


Dependencies
==============

Environment Variables
---------------------

DO_API_TOKEN | Token in order to access DigitalOcean API

Packages
-------

 - Tested on dopy version 3.5
 - ansible  stable-2.0
