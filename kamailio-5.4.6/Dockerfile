FROM kamailio/kamailio:5.4.6-xenial

#LABEL maintainer=Mujickov Ivan <ivan.mujickov@yandex.ru>

VOLUME /etc/kamailio

WORKDIR /etc/kamailio

COPY . . 

ENTRYPOINT ["kamailio", "-DD", "-E"]