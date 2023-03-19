# ansible-system-roles

# Ubuntu commands
## halt
Launch halt on targets

## shutdown
Shutdown targets

# APT
Roles using APT packages manager

## package-common
Install common Ubuntu packages with APT

## package-network
Install network Ubuntu packages with APT

## update
Launch apt update on targets

## upgrade
Launch apt upgrade on targets

# NALA
Roles using NALA packages manager

## nala-install
Install NALA on target

## nala-update
Launch update on targets with NALA

## nala-upgrade
Launch upgrade on targets with NALA

## package-common
Install common Ubuntu packages with NALA

## package-network
Install network Ubuntu packages with NALA

# certificate
Generate certificates with ansible

## ca-create
Create Certificate Autority

## certificate-create-key
Create key for target

## certificate-create-csr
Create CSR for target

## certificate-create-crt
Sign CSR and generate certificate for target

## certificate-copy
Copy certificate on target

## certificate-create-remote-key
Create key on target host

## certificate-create-remote-csr
Create CSR on target host

## certificate-create-remote-crt
Sign CSR and generate certificate for target

## certificate-create

## certificate-create-simple

# OpenSSL
## openssl-passfile-create
Generate passphrase file to use with OpenSSL locally

## openssl-passfile-remove
Remove passphrase file

## openssl-ca-create
Create Certificate Authority using OpenSSL locally

## openssl-create-key
Create key for target using OpenSSL locally

## openssl-create-csr
Create CSR for target using OpenSSL locally

## openssl-create-crt
Sign CSR with CA to create certificate for target using OpenSSL locally

## openssl-convert-to-pem
Convert key in PEM format using OpenSSL locally

## openssl-copy
Copy all certificate files on target with CA locally

## openssl-remove-certs
Remove certs localy
