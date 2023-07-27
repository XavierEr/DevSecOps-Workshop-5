```
terraform init
```

```
terraform plan -auto-approve -var "do_token=${DO_PAT}" -var "ssh_private_key=/root/workshop01/id_rsa" -var "docker_host=<docker nginx>" -var "docker_cert_path=/root/.docker/machine/machines/docker-nginx"
```

```
terraform apply -auto-approve -var "do_token=${DO_PAT}" -var "ssh_private_key=/root/workshop01/id_rsa" -var "docker_host=<docker nginx>" -var "docker_cert_path=/root/.docker/machine/machines/docker-nginx"
```