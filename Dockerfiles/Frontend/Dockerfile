FROM alpine
WORKDIR /app
COPY . .
RUN apk add --no-cache apache2 php7-apache2 monit dos2unix
CMD dos2unix /app/start-web.sh && \
ash /app/start-web.sh
#CMD tail -f /dev/null
