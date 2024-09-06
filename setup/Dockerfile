FROM mongo:6.0.18-rc0

WORKDIR /app
COPY replicaSet.js .
COPY setup.sh .

RUN chmod +x /app/setup.sh

CMD ["/bin/bash", "/app/setup.sh"]
