# unifi-docker
Docker container for Ubiquiti Unifi Controller

docker run -p 3478:3478 -p 8080:8080 -p 8081:8081 -p 8443:8443 -p 8843:8843 -p 8880:8880 -p 27117:27117 -p 10001:10001/udp

Ensure to run with 10001 as UDP for auto discover

Volume path should you wish to configure:

/usr/lib/unifi/data
