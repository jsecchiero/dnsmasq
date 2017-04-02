# dnsmasq

Run the container

```
docker run \
   --name dnsmasq \
   -d \
   --net=host \
   -v /etc/dnsmasq.conf:/etc/dnsmasq.conf \
   --log-opt "max-size=100m" \
   jsecchiero/dnsmasq
```
