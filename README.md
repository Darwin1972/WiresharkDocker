# WiresharkDocker

docker run -it --name=tcpdumpnginx --net=container:nginx tcpdump tcpdump -s 0 -i eth0 -w tmp/tcpdump.pcap

docker cp tcpdumpnginx:/tmp/. D:\\OneDrive\\DEV\\ASPNET\_Core\\Projects\\20210513\\WiresharkDocker\\pcap

![](https://user-images.githubusercontent.com/51634515/120391036-c4a52000-c32e-11eb-9030-fd10117e39e8.png)
