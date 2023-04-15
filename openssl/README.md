# ansible-system-openssl-roles
Roles usint OpenSSL to create certificates and keys on CA server

# Root CA initialisation
use openssl-server-install.yml to create and launch CA server installation

## openssl-passfile-create
Create file to store OpenSSL passphrase on CA server

## openssl-init
Create repositories to store OpenSSL files

## openssl-ca-create
Create Root CA certificate and key

## openssl-passfile-remove
Remove OpenSSL passphrase file

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