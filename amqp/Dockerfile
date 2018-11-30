FROM rabbitmq:3-management

COPY enabled_plugins /etc/rabbitmq/
COPY rabbitmq.conf /etc/rabbitmq/
COPY definitions.json /etc/rabbitmq

EXPOSE 5671

VOLUME /run/secrets/webhook
