FROM ubuntu:trusty
LABEL maintainer = "lnreddy1986@gmail.com"
RUN apt-get update && apt-get install apache2 -y
CMD ["apachectl", "-D", "FOREGROUND"]
EXPOSE 80