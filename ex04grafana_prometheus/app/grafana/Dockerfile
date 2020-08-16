FROM grafana/grafana:latest

LABEL maintainer='awasekhirni@gmail.com'

ADD ./provisioning /etc/grafana/provisioning 

ADD ./config.ini /etc/grafana/config.ini

ADD ./dashboards /var/lib/grafana/dashboards 
