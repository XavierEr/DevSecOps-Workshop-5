```
terraform init
```

```
terraform plan -var "do_token=${DO_PAT}" -var "ssh_private_key=/root/.ssh/id_rsa" -var "docker_host=128.199.227.37" -var "docker_cert_path=/root/.docker/machine/machines/docker-nginx"
```

```
terraform apply -auto-approve -var "do_token=${DO_PAT}" -var "ssh_private_key=/root/.ssh/id_rsa" -var "docker_host=128.199.227.37" -var "docker_cert_path=/root/.docker/machine/machines/docker-nginx"
```