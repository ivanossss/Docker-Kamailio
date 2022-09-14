FROM kamailio/kamailio:5.4.6-xenial

#LABEL maintainer=Mujickov Ivan <ivan.mujickov@yandex.ru>


WORKDIR /etc/kamailio

COPY . . 

VOLUME /etc/kamailio

ENTRYPOINT ["kamailio", "-DD", "-E"]