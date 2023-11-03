# Docker container with a ready to use Nginx module for QR-codes generation

Uses *libqrencode v.4.1.x* by Kentaro Fukuchi (see https://github.com/fukuchi/libqrencode, https://fukuchi.org/works/qrencode).

Module code by dcshi (see https://github.com/dcshi/ngx_http_qrcode_module).

Original Docker container by soulteary (see https://github.com/soulteary/ngx_http_qrcode_module).

### Build

```bash
# build all with:
build
# or:
build alpine
build debian
```

### Pull

```bash
docker pull moujikov/ngx_http_qrcode_module:1.0-ngx-1.25.3
docker pull moujikov/ngx_http_qrcode_module:1.0-ngx-1.25.3-alpine
```

### Use

See `examples-docker` and `examples-nginx`
