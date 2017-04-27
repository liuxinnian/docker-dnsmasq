# dnsmasq

Dockerfiles for dnsmasq (on x86 and arm)

## Usage

### X86
	docker run -d --name dnsmasq -p 53:53/tcp -p 53:53/udp --cap-add=NET_ADMIN liuxinnian/dnsmasq:latest-x86
### ARM
	docker run -d --name dnsmasq -p 53:53/tcp -p 53:53/udp --cap-add=NET_ADMIN liuxinnian/dnsmasq:latest-armhf