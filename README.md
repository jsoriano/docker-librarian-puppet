docker-librarian-puppet
=======================

Dockerfiles for base images that use librarian-puppet to be provisioned

How to use them
---------------
1. Use them as an argument for the FROM instruction of your Dockerfile
1. Put a librarian Puppetfile in the same directory of your Dockerfile
1. Put a puppet file in manifests/site.pp with your provisioning
