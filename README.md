# cb-grafana-monitoring

A set of services in order to store and visualize monitoring metrics from Couchbase

## Stats Polling

The idea is to poll the Couchbase REST service frequently in order to fetch the most relevant metrics and store them as a data point in the target bucket.

## Stats Gathering

We will use the Grafana general JSON data source for this.
