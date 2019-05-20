#FROM alpine:3.4
FROM ubuntu:xenial

ENTRYPOINT ["openvpn"]
VOLUME ["/vpn"]
COPY client.conf /vpn-config

#RUN apk add --no-cache openvpn
RUN apt-get update -qq && apt-get install -y openvpn easy-rsa 
