# Helm Charts

Collection of basic [helm charts](https://helm.sh) to be used in labs.

## Description
### This is a fork of https://github.com/ricardo-aires/helm-charts this repo only for ksqldb
### this repo is maintain by Panna ABDUL HAKIM https://github.com/AHPanna/helm-charts
## Install

This repository holds some helm charts developed to be use in laps. To add the chart repository

```helm repo add ahpanna https://ahpanna.github.io/helm-charts/```
``` helm install ksqldb ahpanna/ksqldb -f myVar.yaml```


## Available Charts
- ksqldb

### Confluent

Helm charts that deploy components of the [Confluent Platform](https://www.confluent.io/product/confluent-platform) (open source and community).


- [ksqldb](./charts/ksqldb/)
