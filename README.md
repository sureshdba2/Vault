# Vault

## Introduction

HashiCorp Vault is a tool for securely accessing secrets. Vault provides a unified interface to any secret, while providing tight access control and recording a detailed audit log. AppZ currently offers Vault-1.2.

### Features:

1. Fully managed stateful Vault-1.2 deployment using GitOps from Client’s Git repository.
1. Secure Secret Storage: Arbitrary key/value secrets can be stored in Vault. Vault encrypts these secrets prior to writing them to persistent storage.
1. Vault-1.2 can automatically generate secure secrets for any application like (MySQL, Mariadb, Springboot, and wordpress) in case we didn’t provide the secrets.
1. Built-in logging and monitoring visualization through AppZ Dashboard.

This stack Creates a Vault application using Gitops.

## Documentation: How to use Vault stack
[Vault](https://docs.ecloudcontrol.com/vault-1.2/)
