FROM eclipse-mosquitto:1.5

COPY ./mosquitto.conf /etc/mosquitto/  

ENTRYPOINT /usr/sbin/mosquitto -c /etc/mosquitto/mosquitto.conf
