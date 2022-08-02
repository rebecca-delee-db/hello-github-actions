FROM debian:9.5-slim

ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT ["/entrypoint.sh"]

ADD entry2.sh /entry2.sh
RUN chmod +x /entry2.sh
ENTRYPOINT ["/entry2.sh"]
