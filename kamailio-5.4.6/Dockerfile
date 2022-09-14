FROM kamailio/kamailio:5.4.6-xenial

#LABEL maintainer=Mujickov Ivan <ivan.mujickov@yandex.ru>


WORKDIR /etc/kamailio

COPY kamailio.cfg .
COPY kamctlrc . 

#COPY modules /usr/lib/x86_64-linux-gnu/kamailio/

VOLUME [/etc/kamailio]
RUN apt-get clean && rm -rf /var/lib/apt/lists/*

ENTRYPOINT ["kamailio", "-DD", "-E"]