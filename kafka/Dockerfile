FROM srob/confluent-platform
ADD kafka-docker.sh /usr/bin/kafka-docker.sh
RUN ln -s /confluent-1.0/etc/kafka /etc
CMD /bin/bash /usr/bin/kafka-docker.sh
