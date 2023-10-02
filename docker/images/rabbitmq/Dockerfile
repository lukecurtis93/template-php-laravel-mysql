FROM rabbitmq:3.10.8-management-alpine

RUN cd /plugins && \
    wget https://github.com/rabbitmq/rabbitmq-delayed-message-exchange/releases/download/3.10.2/rabbitmq_delayed_message_exchange-3.10.2.ez && \
    rabbitmq-plugins enable rabbitmq_delayed_message_exchange
