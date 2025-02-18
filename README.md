# Prometheus netflow Exporter

This is an exporter that exposes information gathered from netflow for use by the Prometheus monitoring system.

now support netflow v5 and v9.

## Installation

go get -d

go build

## Usage

```
./netflow_exporter

# You can use loglevel option (default: info)
./netflow_exporter --loglevel warn (debug, info, warn, error, fatal, panic)

```

Visit http://localhost:9191/metrics

## note

I think that netflow is not metric and analystic message.

Label conbination is too much to collect.
