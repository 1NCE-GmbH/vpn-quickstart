#FROM alpine:3.4
FROM ubuntu:xenial

ENTRYPOINT ["openvpn"]
VOLUME ["/vpn"]

#RUN apk add --no-cache openvpn
RUN apt-get update -qq && apt-get install -y openvpn easy-rsa 
