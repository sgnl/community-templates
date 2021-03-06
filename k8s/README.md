# Kubernetes Dashboards Template

Provided by: [bonitoo.io](.)

**This template provides 2 basic Kubernetes dashboards:
`Kubernetes Node Metrics` and `Kubernetes Inventory`. The K8S infrastrucure
supports Google Cloud Platform, AWS and on-premise K8S environments.**


##### Dashboard examples

![Screenshot](img/k8s-nodemetrics-dashboard.png)
![Screenshot](img/k8s-inventory-dashboard.png)


## Included Resources

This template includes the following:

- 2 Labels: `inputs.kubernetes`, `inputs.kube_inventory`, `K8S`
- 2 Dashboards: `Kubernetes Node Metrics`, `Kubernetes Inventory`
- 1 Variables: `bucket`

## Setup Instructions

Set up and install Telegraf `kubernetes` and `kube_inventory` plugins into your
Telegraf configmap.

* https://github.com/influxdata/telegraf/tree/master/plugins/inputs/kubernetes
* https://github.com/influxdata/telegraf/tree/master/plugins/inputs/kube

Visit the dashboard and use the `v.bucket` variable to select which bucket the data is stored in.

## Customizations

n/a

## Contact

Authors: Ivan Kudibal, Tomas Klapka, https://www.bonitoo.io

Github: @ivankudibal
