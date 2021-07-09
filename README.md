# Mongo Helmchart

[![Made with Helm](https://img.shields.io/badge/Made%20with-HELM-orange?style=for-the-badge&logo=helm)](https://helm.sh/)

## How to install?

 ###  1) From source code

  ####  This will install with default values
  * `helm install mongo-helmchart ./mongo-helmchart/`

  ####  This way you can configure `database password`, `deploymeny name` and `namespace`
  * `helm install mongo-helmchart ./mongo-helmchart/ --set database.rootPassword=somethingelse --set database.port=27017 --set application.name=testmongo --set database.namespace=mongodb`
