FROM redis:6-alpine

LABEL author_name Moisés Bites

ENV REDIS_PASSWORD default-password

CMD ["sh", "-c", "exec redis-server --requirepass \"$REDIS_PASSWORD\""]