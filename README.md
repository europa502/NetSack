# NetSack

## Installing Influxdb -

1. Download inluxdb from the website https://portal.influxdata.com/downloads/  or do
```
NetSack@europa:~# wget https://dl.influxdata.com/influxdb/releases/influxdb_1.7.3_amd64.deb
```
2. Install the package -
```
NetSack@europa:~# sudo dpkg -i influxdb_1.7.3_amd64.deb
```

## Installing Grafana

1. Download Grafana from the website https://grafana.com/grafana/download  or do
```
NetSack@europa:~# wget https://dl.grafana.com/oss/release/grafana_5.4.3_amd64.deb
```
2. Install the package
```
NetSack@europa:~# sudo dpkg -i grafana_5.4.3_amd64.deb
```

## Installing ModSecurity

1. Download it from https://modsecurity.org/download.html and install it by reading the instructions given. If you're unable to install it from the command line in Debian/Ubuntu, do -
```
NetSack@europa:~# sudo apt-get install libapache2-mod-security2
```

