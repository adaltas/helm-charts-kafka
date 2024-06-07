# Helm Charts

Collection of basic [helm charts](https://helm.sh) to be used in labs.

## Description

This is a fork of https://github.com/ricardo-aires/helm-charts this repo only for ksqldb, kafka-connect, kafka-connect-ui
This repo is maintain by Adaltas https://github.com/adaltas/helm-charts-kafka

## Install

This repository holds some helm charts developed to be use in laps. To add the chart repository

```bash
helm repo add adaltas https://adaltas.github.io/helm-charts/
helm install ksqldb adaltas/ksqldb -f myVar.yaml
helm install kafka-connect adaltas/kafka-connect -f myVar.yaml
helm install kafka-connect-ui adaltas/kafka-connect-ui -f myVar.yaml
```

## Available Charts

- ksqldb
- kafka-connect
- kafka-connect-ui

### Confluent

Helm charts that deploy components of the [Confluent Platform](https://www.confluent.io/product/confluent-platform) (open source and community).


- [ksqldb](./charts/ksqldb/)
- [kafka-connect](./charts/kafka-connect/)
- [kafka-connect-ui](./charts/kafka-connect-ui/)
