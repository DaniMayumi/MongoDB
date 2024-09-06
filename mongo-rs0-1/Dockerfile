FROM mongo:6.0.18-rc0

WORKDIR /usr/src/configs

COPY mongo.conf .

EXPOSE 27017

CMD ["--config", "./mongo.conf"]
