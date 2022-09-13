FROM kamailio/kamailio:4.4.6-jessie

#LABEL maintainer=Mujickov Ivan <ivan.mujickov@yandex.ru>

WORKDIR /etc/kamailio
COPY . . 

COPY modules /usr/lib/x86_64-linux-gnu/kamailio/

VOLUME [/etc/kamailio]
RUN /bin/sh -c apt-get clean && rm -rf /var/lib/apt/lists/*


ENTRYPOINT ["kamailio", "-DD", "-E"]