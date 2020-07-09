# media-lab
Ansible playbooks to setup media-server on a raspberry pi


```
docker-compose run --rm control-machine site.yml -i hosts.ini --ask-pass
```

```
docker-compose run --rm --entrypoint "ansible-vault encrypt_string --name test" control-machine
```

```
mount -o anon \\192.168.1.210\mnt\mediahub Z:
```