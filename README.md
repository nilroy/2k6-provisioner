# Shibpurhub-provisioner
This repo contains tools and chef cookbooks to install and maintain 2k6 systems.

##Supporting OS
* Ubuntu 14.04

## Provisioning
A user need sudo permission to provision

* Clone this repo
* Run provioner script

`#./provisioner.sh --env <environment> --role <role> --name <servername>`

> Note: Roles can be mongodb,elasticsearch or mongo_es (includes both mongodb and elasticsearch). Environment can be staging/prod.
You can find all roles in [roles](https://github.com/nilroy/2k6-provisioner/tree/master/dna)

## Mongodb authentication
By default mongodb is installed without any users created. Follow instructions in [https://docs.mongodb.org/v3.0/tutorial/enable-authentication/#add-users-after-enabling-access-control]() to create users

## Contibuting

* Fork the project
* Contribute your code
* Commit your changes.
* Rebase your branch with the upstream so that you have the latest changes (https://github.com/edx/edx-platform/wiki/How-to-Rebase-a-Pull-Request)
* Create a pull request
