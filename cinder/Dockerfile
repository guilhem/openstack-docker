FROM python:2
MAINTAINER Guilhem Lettron "guilhem@lettron.fr"

RUN virtualenv /app
RUN /app/bin/pip install --no-cache-dir git+https://github.com/openstack/cinder.git@master
