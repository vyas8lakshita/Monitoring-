To install Prometheus on your machine, follow the below listed steps. 

wget https://github.com/prometheus/prometheus/releases/download/v2.43.0/prometheus-2.43.0.linux-amd64.tar.gz

tar -xvf prometheus-2.43.0.linux-amd64.tar.gz

cp -r . /usr/local/bin/prometheus

ls /usr/local/bin/prometheus

sudo vi /etc/systemd/system/prometheus.service    # Content of prometheus.service file has also been provided in this repo

sudo service prometheus start

sudo service prometheus status

To install alertmanager follow the below listed steps 

 wget https://github.com/prometheus/alertmanager/releases/download/v0.25.0/alertmanager-0.25.0.linux-amd64.tar.gz
 
 tar -xvf alertmanager-0.25.0.linux-amd64.tar.gz
 
 cp -r . /usr//local/bin/alertmanager
 
 sudo vi /etc/systemd/system/alertmanager.service 
 
 sudo service alertmanager start

sudo service alertmanager status
