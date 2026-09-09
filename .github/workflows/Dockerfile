FROM ghcr.io/home-assistant/base:latest

RUN \
    apk update && \
    apk upgrade

COPY rootfs /

# RUN chmod +x /etc/s6-overlay/s6-rc.d/ha-addon/run