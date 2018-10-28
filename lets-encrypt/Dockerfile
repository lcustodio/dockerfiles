FROM certbot/certbot
VOLUME ["/data"]
RUN (cd ./src/certbot/plugins && pip install certbot-dns-google && certbot plugins)
