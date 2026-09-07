# Paperless-ngx Home Assistant add-on

This add-on runs Paperless-ngx on `aarch64` and uses the existing `redis-poc` add-on as its Redis broker.

## Requirements

- Start the `redis-poc` add-on first.
- Keep Redis reachable as `redis-poc` on port `6379`, or change `redis_host` and `redis_port` in the add-on configuration.
- The add-on uses SQLite. Paperless data and the SQLite database are stored in the add-on data directory.
- Imported and exported documents are stored below `/share/paperless-ngx`.

The web interface is available on port `8000`.

This initial add-on does not bundle Gotenberg or Apache Tika. Advanced document conversion features that require those services need a separate deployment of the corresponding services.
