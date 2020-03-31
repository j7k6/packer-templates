```bash
packer build -var "ssh_pubkey=$(cat ~/.ssh/id_rsa.pub)" -var "root_password=P@ssw0Rd123" bionic.json
```
