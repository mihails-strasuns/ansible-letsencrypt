1. Modify `roles/certificates/vars/main.yml` to specify desired paths used on
   server to store certificates
2. Create private key to be used for the account management and put it into the
   root of this repo named as `le.key`
3. Modify certs.yml to use domain names you need to generate certificate for.
   For each domain name copy the whole block and modify `vars` accordingly.
