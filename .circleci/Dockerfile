FROM httpd:2.4
RUN apt-get update -y && apt-get -y install git
COPY ../app/ /usr/local/apache2/htdocs/
