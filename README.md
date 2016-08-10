# ansible-docker-registry

Creating a private docker registry in AWS:

#Variables in playbooks

```

server_name:     "docker-registry.vishnudxb.me"
ssl_bundle_crt:  "/etc/nginx/ssl/ssl-bundle.crt"
ssl_crt_key:     "/etc/nginx/ssl/ssl-cert.key"

```

#AWS instance tag name

The playbook will identified the instance using the tag name ie docker-registry

#To-Do

- Authorization for users inside the registry.
