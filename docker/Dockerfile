FROM docker.bsm.utility.valapp.com/squid/squid:v3.3.8-1

COPY squid.conf /etc/squid3/squid.conf
COPY entrypoint.sh /sbin/entrypoint.sh
RUN chmod +x /sbin/entrypoint.sh

ENTRYPOINT ["/sbin/entrypoint.sh"]