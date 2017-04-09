# dnsmasq

Run the container

```
docker run \
   --name dnsmasq \
   --restart=always \
   --privileged \
   --net=host \
   -d \
   -v $(pwd)/dnsmasq.conf:/etc/dnsmasq.conf \
   --log-opt "max-size=100m" \
   jsecchiero/dnsmasq
```

```
docker run \
   --name dnsmasq \
   --restart=always \
   --privileged \
   --net=host \
   -d \
   -v $(pwd)/dnsmasq.conf:/etc/dnsmasq.conf \
   --log-opt "max-size=100m" \
   jsecchiero/dnsmasq_armhf
```
