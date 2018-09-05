# Nexus

Your task is to prepare an ansible role (or roles), which will install the latest version of
Sonatype Nexus with all of its dependencies to a virtual server. The requirements are to use
Linux CentOS latest version as the operating system and for the Nexus interface to be available
on port 8080 (this is different from the default 8081).


As an added bonus, install a reverse proxy on the same VM (apache httpd preferred, but not required)
and implement access to the nexus interface via https (443).

 
You can use any component you wish, you can also reuse roles you find on Ansible Galaxy,
but you must be able to understand (and modify) the roles you have used in your solution.
