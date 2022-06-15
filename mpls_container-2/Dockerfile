FROM frrouting/frr:latest
RUN apk update && apk add tcpdump
COPY vtysh.conf /etc/frr/
COPY frr.conf /etc/frr/