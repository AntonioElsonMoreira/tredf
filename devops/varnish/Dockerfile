# syntax=docker/dockerfile:1
FROM varnish:7.6

LABEL maintainer="Antonio Elson <antonio.elson@gmail.com>" \
      org.label-schema.name="tredf-varnish" \
      org.label-schema.description="Treinamento TRE-DF Varnish image." \
      org.label-schema.vendor="Antonio Elson"

COPY etc/varnish.vcl /etc/varnish/default.vcl
