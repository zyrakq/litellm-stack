FROM localhost/litellm:amd64

WORKDIR /app

COPY config.yaml .

EXPOSE 4000/tcp

CMD ["--port", "4000", "--config", "config.yaml"]