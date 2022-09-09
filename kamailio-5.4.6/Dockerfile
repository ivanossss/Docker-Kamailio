FROM kamailio/kamailio:5.4.6-xenial

WORKDIR /etc/kamailio/

COPY . .

CMD [ "/bin/sh" ] 

ENTRYPOINT ["kamailio" "-DD" "-E"]