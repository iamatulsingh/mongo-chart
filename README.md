# Mongo Helmchart

![Build](https://github.com/iamatulsingh/mongo-helmchart/actions/workflows/release.yml/badge.svg)

[![Made with Helm](https://img.shields.io/badge/Made%20with-HELM-orange?style=for-the-badge&logo=helm)](https://helm.sh/)

## How to install?

 ###  1) From source code
 
  ####  Change directory
  * `git clone https://github.com/iamatulsingh/mongo-helmchart.git && cd mongo-helmchart/chart`

  ####  This will install with default values
  * `helm install mongo-helmchart ./mongodb/`

  ####  This way you can configure `database password`, `deploymeny name` and `namespace`
  * `helm install mongo-helmchart ./mongodb/ --set database.rootPassword=somethingelse --set database.port=27017 --set application.name=testmongo --set database.namespace=mongodb`
