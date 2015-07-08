FROM guilhem/keystone-http
MAINTAINER Guilhem Lettron "guilhem@lettron.fr"

EXPOSE 35357

RUN ln -s /app/keystone.py /app/admin
COPY uwsgi.admin.ini /etc/keystone/

ENTRYPOINT ["/app/bin/uwsgi", "--die-on-term", "--ini", "/etc/keystone/uwsgi.admin.ini"] 
