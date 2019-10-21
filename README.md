# Package to method SpeedTest

Tools Use:
CENTOS
* yum  install  netsniff-ng

DEBIAN
* apt-get install  netsniff-ng

File big_packge.txf
Big package.. IPV4 UDP.

Configure IP address source and destination.


How to start test:    (background processing)

* nohup trafgen --dev enp1s0 --conf big_packge.txf -V -k 100 --cpus 1 &

