FROM haproxy:2.4.17

# add missing socket path
USER root
RUN chown haproxy /var/run/ -R
USER haproxy
