FROM guilhem/keystone-common

MAINTAINER Guilhem Lettron "guilhem@lettron.fr"

ADD https://raw.githubusercontent.com/openstack/keystone/master/httpd/keystone.py /app/keystone.py

RUN /app/bin/pip install uwsgi

COPY uwsgi.ini /etc/keystone/
