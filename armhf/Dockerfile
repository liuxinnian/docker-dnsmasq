FROM easypi/alpine-arm:build

MAINTAINER Xinnian Liu <liuxinnian@palmax.com>

VOLUME /etc/dnsmasq.d

RUN apk --no-cache add dnsmasq

CMD ["dnsmasq", "--keep-in-foreground", "--conf-dir=/etc/dnsmasq.d/,*.conf", "--log-facility=-"]

EXPOSE 53/tcp
EXPOSE 53/udp
