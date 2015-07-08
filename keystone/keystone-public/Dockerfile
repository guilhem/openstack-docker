FROM guilhem/keystone-http
MAINTAINER Guilhem Lettron "guilhem@lettron.fr"

EXPOSE 5000

RUN ln -s /app/keystone.py /app/main
COPY uwsgi.main.ini /etc/keystone/

ENTRYPOINT ["/app/bin/uwsgi", "--die-on-term", "--ini", "/etc/keystone/uwsgi.main.ini"] 
