FROM kamailio/kamailio:4.4.6-jessie

#LABEL maintainer=Mujickov Ivan <ivan.mujickov@yandex.ru>

VOLUME /etc/kamailio

WORKDIR /etc/kamailio
COPY . . 

WORKDIR /usr/lib/x86_64-linux-gnu/kamailio/
COPY modules .

ENTRYPOINT ["kamailio", "-DD", "-E"]