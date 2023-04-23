# ansible-system-openssl-roles
Roles usint OpenSSL to create certificates and keys on CA server

# Root CA initialisation
use openssl-server-install.yml to create Root and Sub CA server

## openssl-passfile-create
Create file to store OpenSSL passphrase on CA server

## openssl-passfile-remove
Remove OpenSSL passphrase file

## openssl-init
Create repositories to store OpenSSL files

## openssl-create-root-ca
Create Root CA certificate and key

## openssl-create-sub-ca
Create Sub CA certificate and key

## openssl-pull-sub-ca-certs
Copy Sub CA certs from Root CA on localhost

## openssl-push-sub-ca-certs
Copy Sub CA certs from localhost to Sub CA server

# Certificates creation
Roles to generate keys and certificates

## openssl-create-key
Generate key

## openssl-create-csr
Generate OpenSSL configuration file for server or client and generate CSR

## openssl-create-crt
Use OpenSSL configuration file and CSR to generate certificate signed by CA

## openssl-remove-certs
Remove all certs