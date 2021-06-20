# mongo-helmchart

[![Made with Helm](https://img.shields.io/badge/Made%20with-HELM-orange?style=for-the-badge&logo=helm)](https://www.espressif.com/en/products/socs/helm)

## How to install?

 ####  This will install with default values
 * `helm install ./mongo-chart/ mongo-chart`

 ####  This way you can configure `database password`, `deploymeny name` and `namespace`
 * `helm install ./mongo-chart/ mongo-chart --set database.rootPassword=somethingelse --set application.name=testmongo --set database.namespace=mongodb`
