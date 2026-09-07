FROM ghcr.io/paperless-ngx/paperless-ngx:latest

COPY rootfs /

RUN chmod +x /usr/local/bin/ha-paperless-entrypoint

ENTRYPOINT ["/usr/local/bin/ha-paperless-entrypoint"]
