#
# http static server one-liners
#

FROM busybox:1.30

ADD * /app/
WORKDIR /app

EXPOSE 80
CMD ["busybox", "httpd", "-f", "-p", "80"]
