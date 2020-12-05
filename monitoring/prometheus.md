# Prometheus



Prometheus is an open source monitoring tool that enables system engineers to monitor remote servers/services. 



## Introduction

[Introduction to Prometheus](https://www.youtube.com/watch?v=5o37CGlNLr8)



## Setting up Prometheus



To setup Prometheus, we need to have Prometheus server that queries node exporters for server statistics. Each server must have a node exporter installed.

### Setting up the Prometheus monitoring system

#### 1. Download Prometheus

Check out the Prometheus page and download the appropriate monitoring system for your Operating system [Download page](https://prometheus.io/download/). I am using Ubuntu so I will go ahead and download the monitoring system for linux  as displayed in the image below:

![Download Prometheus monitoring tool](./images/download_prometheus.png)

#### 2. Unzip the files and run Prometheus

Switch to the download directory, unzip the files, and run the Prometheus monitoring system.

```bash
# Unzip
tar -xzf prometheus-2.23.0.linux-amd64.tar.gz
# Change directory
cd prometheus-2.23.0.linux-amd64
# Run Prometheus monitoring system
./prometheus
```

To visualize the monitoring system browse to localhost:9090 and you will end up with a monitoring system as given below:

![Prometheus monitoring tool](./images/monitoring_prometheus.png)

Congratulations! Your monitoring system is up and running.



### Add node exporter to all servers







