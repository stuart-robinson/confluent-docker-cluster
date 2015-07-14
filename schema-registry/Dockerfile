FROM srob/confluent-platform
ADD schema-registry-docker.sh /usr/bin/schema-registry-docker.sh
RUN ln -s /confluent-1.0/etc/schema-registry /etc
CMD /bin/bash /usr/bin/schema-registry-docker.sh
