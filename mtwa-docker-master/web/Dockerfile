FROM dipinjain/mtwa:base
LABEL maintainer="jain.dipin84@gmail.com"
LABEL Description="Web tier image for the multi-tier web app."

RUN service apache2 restart

EXPOSE 80/tcp
EXPOSE 443/tcp
# Start apache server
ENTRYPOINT ["/sbin/entrypoint.sh"]
