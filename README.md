# Honeypot-Elastic Stack
Inspired by T-Pot from Deutsche Telekom AG Honeypot Project

#### Environment
* 1 server RAM 2GB, 1vCPU,Storage 25GB, 1 IP Public --> Honeypot Server
* 1 server RAM 8GB,4 vCPU Storage 80GB,--> Elastic Stack Server
* VPN Connection
* Honeypot : Cowrie, Dionaea
* Elastic Stack 6.4: Elasticsearch, Logstash, Kibana, Filebeat
* GeoIP Database : MaxMind
* IP Reputation Database : Deutsche Telekom

#### Topology
![topology](https://github.com/riupie/honeypot-elk/blob/master/topology.png)
