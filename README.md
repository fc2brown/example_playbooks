# example_playbooks

# server_provisioning.yml
server provisioning exercise

============================

Given root access to a fresh Ubuntu server named 'exercise1.example.com',

perform the following using Ansible as much as possible:

- Install Apache and MySQL server.

- Create a 'deploy' user for the system and for the MySQL server.

- Install RVM under the 'deploy' user.

- Install the latest stable version of Ruby 2.3.x under the 'deploy' user.

- Install Phusion Passenger under Apache.

- Create a DocumentRoot directory for the site under /var/www/html with ownership and permissions such that:
  -  the 'deploy' user has read/write access
  -  the webserver has read/write access to any log files and read-only access to everything else
  -  and that other users have no access.