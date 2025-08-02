FROM ghcr.io/home-assistant/aarch64-base:latest

RUN \
    apk update && \
    apk upgrade

WORKDIR /app

COPY . /app

CMD ["./HA.Addon.Huawei.Sun2000"]
