# Idempotence-in-HTTPD-with-Ansible
Part of ARTH Task 11.3

Whenever we start a httpd server on our machine (Virtual Machine here),
it runs with whatever configuration it had before starting. Now, we may
need to reconfigure some areas or edit our webpages. So, only by saving
the edits, the httpd server will not be reconfigured automatically. The httpd
service needs to be restarted to make the changes visible.
Now, Idempotence means that applying an operation once or applying it
multiple times has the same effect.
So, from these statements, we can conclude that HTTPD Service is not
Idempotence in nature.
So, our job will be to make the working of HTTPD server Idempotence in
nature, using an Ansible playbook code.
