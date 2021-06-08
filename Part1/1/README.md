<h1>Problem Statement</h1>
Write an ansible playbook for installing nginx, docker, logrotate. Ensure nginx container is running on port 8080 on host and log rotation is cleaning the logs of stdout of nginx container once it reaches 100mb. (Separate roles should be created for the tasks mentioned inline)

<h1>Solution</h1>
Ansible playbooks to install docker, nginx and logrotate

<h1>Instructions</h1>

To run a particular role, say docker:

```cd Part1/1/
   ./ansible/docker.yml --inventory localhost_inventory
```
